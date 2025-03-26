# Makefile for Banker's Algorithm

# Compiler and flags
CC = gcc
CFLAGS = -Wall -static

# Target executable
TARGET = bankers

# Source files
SRC = bankers.c

# Default target
all: $(TARGET)

# Rule to build the executable
$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

# Clean rule
clean:
	rm -f $(TARGET) *.o

# Phony targets
.PHONY: all clean 