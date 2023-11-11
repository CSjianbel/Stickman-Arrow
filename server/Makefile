CC = gcc
FLAGS = -std=c17 -Wshadow -Wall -Wno-unused-result 
OUT = server

gcpt:
	$(CC) $(FLAGS) -O2 -o $(OUT).out $(OUT).c

debug:
	$(CC) $(FLAGS) -O0 -ggdb3 -o $(OUT).out $(OUT).c
	
clean: 
	rm $(OUT)
