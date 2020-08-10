# Structures + Binary Files

Learning Goals
==============

* Understand structures
* Read data from a binary file using `fread`
* Write data to a binary file using `fwrite`
* Call `qsort` function to sort an array of structure 
* Write your own Makefile for testing
* Check memory error using `valgrind`


Makefile
========

You need to write your own Makefile from now on.  Makefile can save a
lot of time because you do not have to type many characters when you
test your program.

Check Memory Leak
=================

Your program must not crash and must not leak memory.  **From now on,
you will lose one point for every leaked byte.** The leaked bytes will
accumulate across all test cases in each assignment. If your program
leaks memory, it is very likely that you will receive zero.  Please
use `valgrind` to check memory errors. A program that leaks memory is
like an airplane that leaks fuel. Neither can be accepted.


Functions Needed
================

* `int main(int argc, char * * argv)`
* `int countVector(char* filename)`
* `bool readVector(char* filename, Vector * vecArr, int size)`
* `bool writeVector(char* filename, Vector * vecArr, int size)`
* `int compareVector(const void *p1, const void *p2)`
	
Structure
=========
The structure looks like
``` 
    	#typedef struct
	{
		int x;
		int y;
		int z;
	} Vector;
```

It contains 3 integer variables, `x`, `y`, and `z`. 

Summary
========

The goal of this homework is: To read from a binary file, into an
array of `Vector` structure using the `fread` function. Then to sort,
using `qsort`, this array of structures based on the attribute of `x`
first.  If two vectors have the same `x` value, compare the `y`
values.  If two vectors have the same `y` value, compare the `z`
values.  Finally, write the sorted array of structures to the output
file, using `fwrite`.
	
WHAT TO SUBMIT
==============

You **must** follow the instructions precisely. Failing to follow
these instructions will likely make you receive zero in this
assignment.  Your score **is determined by your submission**, nothing
else.  The teaching staff is strictly prohibited seeing anything on
your computer for grading.

```
zip hw08.zip main.c hw08.c
```

Upload `hw08.zip`.

Please notice that you do not need to submit `Makefile`.  If you submit `Makefile, it will not be graded.

Frequently Asked Questions
==========================

Q: If `Makefile` is not submitted and graded, why should I do it?

A: Learning to to write `Makefile` because doing so is good for you.

Q: If learning `Makefile` is good, why is `Makefile` not graded?

A: Because it is important to understand that some things are good for
you, even though you get no point directly.  How many points do you
get by eating dinner? How many points do you get by sleeping? If you
get no points eating and sleeping, why do you do these things? 

Q: What will happen if I do not learn how to write `Makefile`?

A: You will regret.

Q: Do you mean that I have to decide what to do?

A: Yes. You should decide what to do.  This class gives you
suggestions. You decide what to do.

Q: Why do you give this decision to students?

A: Because you should be responsible for your decisions and actions.

