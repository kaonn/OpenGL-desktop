# I am a comment, and I want to say that the variable CC will be
# the compiler to use.
CC=g++
# Hey!, I am comment number 2. I want to say that CFLAGS will be the
# options I'll pass to the compiler.
CFLAGS=-c -Wall
OPENGL_FLAGS=-lglfw -lGLEW -framework Cocoa -framework OpenGL -framework IOKit -framework CoreVideo
INCLUDE_PATH=/
all: test

test: test.o
	$(CC) -o test test.cpp  $(OPENGL_FLAGS)
triangle: triangle.o
	$(CC) -o triangle triangle.cpp  $(OPENGL_FLAGS)

clean:
	rm -rf *o hello