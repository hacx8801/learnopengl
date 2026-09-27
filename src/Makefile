COMPILER=g++
FLAGS=-o3
FILES=*.c *.cpp
LINK=-lglfw
BIN=main.out

all: build

build:
	$(COMPILER) $(FILES) $(FLAGS) $(LINK) -o $(BIN)

run: build
	./$(BIN)

clean:
	@rm -rf *.out
