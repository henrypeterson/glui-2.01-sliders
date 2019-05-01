CC=g++
CFLAG=-lm -framework OpenGL -framework GLUT -Wno-deprecated-declarations -Wno-c++11-compat-deprecated-writable-strings ./libglui.a
SOURCES=sample.cpp

all: clean project

project: sample.cpp
	$(CC) $(CFLAG) -o out $(SOURCES)

clean:
	rm -f out

c: clean
