# Location of where hello.c is stored in
SRCDIR=./src
LIBS=./include

# Name of the compiler, GNU GCC in this case
CC=gcc

# Any include directories
# INCLUDE = ./lib/macos/include
INCLUDE = C:\msys64\mingw64\include

# Any flags for the compiler
# CFLAGS = -g -I$(INCLUDE) -c
CFLAGS = -g -I$(LIBS) -I$(INCLUDE) 

# Any libraries to link with
# LIBS = ./lib/win/lib/

# Extra flags to give to compilers when they are supposed to invoke the linker
LDFLAGS = -lmingw32 -lSDL2main -lSDL2 -lSDL2_image -mwindows

TARGETS = final

all:  
	@echo "Building Final"
	$(CC) $(CFLAGS) $(SRCDIR)/alien.c $(SRCDIR)/spaceman.c $(SRCDIR)/world.c $(SRCDIR)/main.c $(LDFLAGS) -o aliens

clean:
	rm  rm $(TARGETS)
