# ***
# *** DO NOT modify this file 
# ***

WARNING = -Wall -Wshadow --pedantic
ERROR = -Wvla -Werror
GCC = gcc -std=c99 -g $(WARNING) $(ERROR) 

TESTFALGS = -DTEST_CREATELIST -DTEST_ELIMINATE -DTEST_DELETENODE -DDEBUG

SRCS = main.c hw10.c
OBJS = $(SRCS:%.c=%.o)

hw10: $(OBJS) 
	$(GCC) $(TESTFALGS) $(OBJS) -o hw10

.c.o: 
	$(GCC) $(TESTFALGS) -c $*.c 

testall: test1 test2 test3 

test1: hw10
	./hw10 6 3 > output1
	diff output1 expected/expected1

test2: hw10
	./hw10 6 4 > output2
	diff output2 expected/expected2

test3: hw10
	./hw10 25 7 > output3
	diff output3 expected/expected3

memory: hw10
	valgrind ./hw10 12 5

clean: # remove all machine generated files
	rm -f hw10 *.o output?


