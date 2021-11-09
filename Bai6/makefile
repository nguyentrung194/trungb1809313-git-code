helloworld: helloworld.o mylib
	gcc -o helloworld helloworld.o libmylib.a
helloworld.o: helloworld.c
	gcc -c helloworld.c
mylib: hello.o bonjour.o
	ar crv libmylib.a hello.o bonjour.o
hello.o: hello.c
	gcc -c hello.c
bonjour.o: bonjour.c
	gcc -c bonjour.c
