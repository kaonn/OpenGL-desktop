# I am a comment, and I want to say that the variable CC will be
# the compiler to use.
CC=g++
# Hey!, I am comment number 2. I want to say that CFLAGS will be the
# options I'll pass to the compiler.
CXXFLAGS=-Wall -std=c++11 -std=gnu++0x
OPENGL_FLAGS=-lglfw3 -lGLU -lGL -lGLEW `pkg-config --static --libs x11 xrandr xi xxf86vm` 
INCLUDE_PATH=/
all: test

test: test.o
	$(CC) $(CXXFLAGS) -o test test.cpp  $(OPENGL_FLAGS)
triangle: triangle.o
	$(CC) $(CXXFLAGS) -o triangle triangle.cpp  $(OPENGL_FLAGS)

clean:
	rm -rf *o hello
