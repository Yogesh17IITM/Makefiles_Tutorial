#	Using dependencies
#	^^^^^^^^^^^^^^^^^^
#	This allows us to compile specific files.
#	You can try this by typing "make <dependency>", say for eg. make hello.o

all: hello

hello: main.o factorial.o hello.o
	g++ main.o factorial.o hello.o -o hello

main.o: main.cpp
	g++ -c main.cpp

factorial.o: factorial.cpp
	g++ -c factorial.cpp

hello.o: hello.cpp
	g++ -c hello.cpp

clean:
	rm *.o hello
