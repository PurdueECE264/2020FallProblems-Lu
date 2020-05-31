# 2020 Fall Homework Assignments for Purdue ECE 264 "Advanced C Programming"

Instructor: Yung-Hsiang Lu

Welcome to ECE 264

Due to the uncertainty of COVID-19, this course is more flexible than
past offerings.  If you encounter any situation and require special
accommodation, please communicate with the instructor or Purdue Office
of the Dean of Students.  Please follow the advice of health
experts. Stay safe and healthy.

Please refer to Purdue's Brightspace pages about grading.

This class is going through major restructuring to reflect the needs
of students, new technologies in software engineering, and
expectations from industry.

The problems are classified into three parts:

* Part 1: Each focuses on a narrowly defined problem.

* Part 2: Each requires integration of the knowledge and skills for solving several related problems.

* Part 3: New assignments as experiments

Part 1 Basic
============

* HW01 Linux: Linux commands, `gcc`, `make`
* HW02 Sort: Selection Sort. Array. Testing.
* HW03 Cake: Who gets the cake? Array, Makefile. Testing.
* HW04 File: Read characters from a file and count the occurrences. `fopen`, `fclose`, `fgetc`
* HW05 Sum: Read integers and add them, pointer. `fscanf`, `fprintf`
* HW06 Word: Read lines and count a word's occurrences, string. `fgets`, `strstr`
* HW07 QSort: Read data from file, call `qsort` to sort numbers, save data to file
* HW08 Structure: Read binary file, sort, write results to another file
* HW09 MergeSort: Use merge sort to sort an array of integers. Recursion
* HW10 Cake2: Who gets the cake? Use linked list.

Part 2 Integration
==================

* HW11 Shuffle1: Shuffle cards once. Recursion.
* HW12 Shuffle2: Shuffle cards multiple times. Recursion.
* HW13 Arithmetic1: Perform arithmetic calculation using postfix expression.
* HW14 Arithmetic2: Convert an infix expression to postfix.
* HW15 BinaryTree1: Build a binary tree from in-order and post-order
* HW16 BinaryTree2: Print the path from a node to the root
* HW17 Maze: find the shortest distances between the source to all reachable locations
* HW18 Memory: allocate and free memory blocks and bit operations
* HW19 Sudoku: solve Sudoku problems (without the need of backtrack)
* HW20 K-mean Data Clustering: Unsupervised learning

Par 3 Experiments (Optional)
============================

* HW21 Shortest Path: find the shortest paths from a single source to all destinations
* HW22 Shortest Path: find the shortest paths from a single source to a single destination
* HW23 Neural Networks: train a three-layer neural networks for logic gates

ECE 264 Uses Linux
==================

This course uses Linux.  Engineering Computer Networks (ECN,
https://engineering.purdue.edu/ECN) is the IT (Information Technology)
for Purdue's College of Engineering.  ECN manages many Linux
computers. Your submitted assignments will be graded on ECN Linux. You
are strongly encouraged to write and test your programs on ECN Linux
computers.  The only way to grade your submissions is to use ECN
Linux.  For privacy and security, the teaching staff cannot touch your
computer.  The teaching staff cannot grade your programs on your
computer.  Thus, please do not say, "My program runs on my computer."
This statement is irrelevant.

The first homework (HW01) will explain how to use Linux computers. If
you have no ECN account, please contact ECN. Please *do not* as the
instructor. The instructor is not authorized to create ECN account.
If you ask the instructor, the response is "Please ask ECN".

You must not use Windows, MacOS, Android, or any other operating
systems.  Even though your C programs should work if you follow the C
language standards, developing your C programs outside Linux may
create unnecessary trouble.

Registration Questions
======================

If you have questions about registration, please contact the ECE
Undergraduate Office
(https://engineering.purdue.edu/ECE/Academics/Undergraduates/UGO/About/Office_Information). The
instructor has no authorization about registration.  If you ask the
instructor questions about registration, the response is "Please
contact the undergraduate office".

Collaborative Learning Environment
==================================

There is a worldwide shortage of qualified software developers.  Based
on an article posted on 2020/05/29 on the website of the Computing
Research Association (or CRA), *"By April 2020, when the impacts of
the pandemic forced overall unemployment up to 15 percent,
unemployment in the computing fields actually dropped to 2.8 percent,
according to an analysis of Bureau of Labor Statistics Current
Population Survey data by the National Foundation for American Policy
(NFAP). An analysis by NFAP of Active Job Postings in Computing
Occupations amplifies this point, noting that between April 14 and May
13, 2020, there were more than 625,000 active vacancies in jobs that
require at least a bachelor's degree in computing."*

ECE 264 encourages everyone to help everyone. Your classmates may
design your next apps, the next medical devices that ensure your
health, the software to make your vehicle safer, smart appliance in
your home... If you help them, they can be better software developers
and design better products for you.

This class uses "absolute grading" (i.e., not curve grading). Your
grade depends on yourself and is unaffected by your classmates. This
class does **not** have the policy that a certain percentage of
students can get A and another certain percentage of students must get
F.  It is possible that everyone gets A, even though this has never
happened before.

You are encouraged to talk to your classmates, exchange ideas, ask
questions, answer questions.  When you have questions, the best place
to ask is the online forum.  Your questions may be answered within an
hour by a classmate. Of course, you are encouraged to answer your
classmates' questions.  You are encouraged to form study groups and
meet regularly (in person or virtually) to review the course
materials, discuss strategies to solve assignments, or prepare for
exams.

How are Programming Assignments Graded?
=======================================

Programming assignments are graded by computer programs. Thus, your
programs must follow the instructions **precisely**. You must
understand that computers are not tolerant. Any "small" (small for
you) mistake can lead to significant loss of points.

More is not better. If the assignment does not ask you to print
anything, your programs must not print anything.  Printing debugging
messages will likely cause significant loss of points.  Some students
say, "My programs print everything needed, and more. Isn't more
better?"  The answer is No. More is not better. Your programs must
follow the specifications precisely.

Why is this course so strict in meeting specifications? Because that
is the expectations of professional software developers.  Computer
software is used in many systems that might cause injuries or loss of
lives (such as flight control or autonomous vehicles). It is critical
to follow the specifications precisely. If you want to pursue
engineering as your career, you must understand the needs of following
specifications.


Structures of Assignments
=========================

At the top of every file, there is clear indication whether you should modify the file or not.  You must follow the instruction.
If you modify a file must not be changed, you will likely lose points.  

Everything you write must be enclosed within

`#ifdef`

and

`#endif`

The reason is that we may replace the functions to give you partial credits by turning on or off specific blocks.  If you write anything outside `#ifdef` and `#endif` and your code happens to have mistakes, the mistakes cannot be removed.  As a result, your program cannot receive partial credits.


If You Find Mistakes
====================

The teaching staff takes significant efforts making these assignments. Despite the efforts, mistakes are
still possible. If you suspect any mistake, please post in the online forum. The more details, the better.
Please include the following information (and any additional information you may have). Thank you.

* Assignment Number
* What do you expect
* What do you see
* The type of computer you are using (please remember that the assignments are designed for Linux)
* Procedure to reproduce the problem
* Suggestions for correction

If You Have Suggestions
=======================

Software development is fast-moving technologies. The teaching staff
takes significant efforts keeping up with recent and proven
technologies. However, it is possible that some technologies are
better than what is used in this class.  If you have any suggestions
about how to improve the class, please share your thought.  Thank you.

Frequently Asked Questions
==========================

* Q: Is there any assignment during a week when there is also an exam?
* A: Yes, for midterm exams.

* Q: Why?
* A: The assignments help you understand the materials and answer exam questions.

* Q: Why are there more assignments than the past semesters?

* A: Computers are not forgiving. A "small" (small to humans) may make
  a computer program non functional. In the past semesters, some
  students made careless mistakes (such as failing to submit all
  needed files) and lost most or all points. As a result, one careless
  mistake may have too much impact in the final grade.  This semester
  breaks the assignments into smaller ones so that each assignment has
  fewer points. Careless mistakes have less impact on the final
  grades.  The covered topics are the same.

* Q: Many assignments have restrictions, such as data types or
  function signatures (return type, argument types). Why? I want total
  freedom because I am very creative. I do not want any restriction at
  all.

* A: The restrictions are needed for grading, in particular, giving
  partial credits when your programs do not work completely. It is
  wrong that total freedom is needed for creativity. True creativity
  is to create within the boundaries of appropriate (and in many cases
  necessary) restrictions. Musicians use the same notations. Painters
  have to understand light and interactions of pigments. Dancers have
  to create with the presence of gravity.

* Q: I don't care about the restrictions. It is not possible to write
  my answers when these restrictions are imposed. 

* A: It is certainly possible writing answers with these restrictions
**because the teaching staff has already written the answers.** If you
think it is not possible, you do not understand the materials.

* Q: I do not care. I must change the files that say, "DO NOT modify
  this file".

* A: You will probably receive zero if you change these files.

* Q: What is the most importance advice you would give?

* A: This course is harder than most students expect. It is extremely
  unlikely that you can finish an assignment quickly. Start homework
  as soon as possible.

* Q: What is your second most important advice?

* A: Understand: "Spend time to save time." Many students want to
  rush. They start coding without studying or thinking. They do not
  spend time learning debugger.  If you rush, it will take longer.

* Q: Why do we learn C language? Is anyone using C?

* A: IEEE reports the "Top Programming Languages" every year. In 2019,
the top five are Python (100), Java (96.3), C (94.4), C++ (87.5) and
R(81.5).  Three of the top five (Java, C, C++) are very similar in
many ways. C++ was inpired by C and Java was inspired by C++. C was
designed to closely reflect the underlying systems (including hardware
structures). Understanding C can help you understand computer
design. When you write C programs, you have to take care of many
details. Some other languages take care of some details (such as
memory management) for you.  It is generally agreed that if you can
write good C programs, you can learn other programming languages more
easily.


WARNINGS: Your Programs Must Not Crash and Must Not Leak Memory
===============================================================

Your program must not crash and must not leak memory in any case.
Memory management is an essential part of writing good C programs.  If
you cannot manage memory, you cannot write good C programs.

You will lose 1 point for every leaked byte. If your program leaks
memory, it is very likely that you will receive zero.

You should know how to check memory errors: using `valgrind` . If your
program leaks memory, it is like an airplane that leaks fuel.  Would
you take a flight if the plane leaks fuel? An airplane should not fly
if it leaks fuel. Your program *DOES NOT* work if it leaks
memory. Don't fool yourself and claim that your program works.  Talk
to professional software developers. Everyone will tell you memory
leak is *unacceptable*.

Keep An Open Mind: It is possible that your programs are wrong
==============================================================

Do not say, "My program works fine when I test it. I am 100% sure my
program is correct.  My program is absolutely perfect."  Many people
have said that and so far all of their programs have problems.  The
teaching staff accepts the possibility that they may be wrong. Please
also open your mind and accept the *possibility* that your program
*may* be wrong.  Before you get angry and think you are not treated
fairly, understand what happens.  The teaching staff provides all
information you need to test your programs.

Computers are Stupid, By Design
===============================

Computers are designed during the second World War and Cold War to
control weapons. As a result, computers are stupid by design.
Computers do exactly what programs tell them to do.  Computers cannot
guess your mind. Computers cannot tolerate "small" mistakes.

Know Your Friends: Everyone in Class
====================================

The teaching staff and your classmates are your friends.  They want to
work with you and help you become a professional software developer.
Many studies have demonstrated that people learn more effectively in
friendly environments.  There is a worldwide severe shortage of good
software developers.  When everyone helps everyone become a better
software developer, everyone benefits.


Regarding Requests
==================

The only way to request regrading is to fill a regrading request in
Brightspace. The regrading request needs detail information to help
understand what is wrong.  This is a large class. Things must be
handled systematically.  If you do not provide the information, it is
not possible for the teaching staff to understand what happens.

*DO NOT TALK* to the teaching assistants or the instructor and demand
regrading.  Filling the regrading request is the only way.

The regrading request will be processed approximately once a
week. Your patience is appreciated.

Regrading is not "free". The teaching staff has to take time to
check. Request regrading only if you actually have reasons.  In the
past, some students requested regrading even when they did not submit
assignments. Some students requested regrading *before* assignments
were graded.  These students said, "Why not? I will lose nothing."
These unreasonable requests wasted the time of the teaching assistants
(they were also students).

To prevent future unreasonable requests, the following penalty is
imposed: If a student requests regrading for an assignment that was
not submitted, the student will lose 50% in the next assignment.

Please understand that preventing these unreasonable requests save the
time of the teaching assistants so that they can respond to reasonable
questions.

Your Rights
===========

ECE 264 is a large class and unintentional mistakes are possible.  It
is unlikely that these mistakes are targeting any specific students.

If you think you are treated unfairly, you can report to the associate
head of ECE for education.  If you are unsatisfied at the results, you
can report to the associate dean of Engineering for education.  If you
are unsatisfied at the results, you can report to the Dean of Students
or the associate provost of education.  



How to Write Correct Programs Efficiently
=========================================

Many people have learned to write programming and become professional
software developers. In fact, many people enjoy writing computer
programs. Many people find programming extremely difficult. What are
the differences between different people? Many factors contribute to
the differences. Here are a few:

* Professional software developers read to learn. Some students do not
  read and prefer the "trial and error" approach: do random things and
  hope to magically make their programs work. These students claim
  that this approach is their way of learning. That makes no
  sense. The foundation of human civilization is to learn from what is
  already discovered by others.

* Professional software developers pay attention to
  details. Professional software developers understand computers
  cannot tolerate "small" mistakes. Some students think they should
  get 99% points if 99% of their program works.  Unfortunately, this
  is not true for computers. Computers are designed to be stupid
  (because computers were created to control weapons) and computers
  cannot tolerate small mistakes.

* Professional software developers assume their programs have problems
  and thus carefully design their programs to prevent, detect, and
  remove mistakes.  Some students believe that their programs are
  always correct and have no plan to prevent, detect, and remove
  mistakes.  

* Professional software developers write small pieces of code each
  time, test thoroughly, before writing another piece of code.  Some
  students write a lot of code and expect everything to work smoothly
  when these pieces are put together.  

* Please read the entire assignments before you ask any question. In
  many cases, your questions have already been answered. If you still
  have questions, please post them online. **DO NOT SEND EMAIL TO THE
  INSTRUCTOR, UNLESS IT IS PERSONAL ISSUES**.


Email Policy
============

This policy is necessary because everyone has exactly 24 hours a day.
The teaching staff must spend time helping the students that really
need help. The teaching staff must not waste on irrelevant things.

The teaching staff will *NOT* answer emails that ask questions
applicable to other students (such as questions about the class or
assignments).  Your email must be used for questions specifically to
you individually.  Before you send email, ask "Is it OK if someone
else sees this?" If the answer is yes, post your message in the online
forum so that everyone in the class can see.  It is very likely that
your classmates answer your questions before the teaching staff.

You are responsible checking the online discussion forum.  The
teaching staff will ignore your email if your questions have already
been answered on the online discussion forum.

Exceptional Needs
=================

If you have exceptional needs, please contact
* Office of the Dean of Students (https://www.purdue.edu/odos/)
* Disability Resource Center (https://www.purdue.edu/drc/about/index.php)
* Student Health Center (https://www.purdue.edu/push/Contact/index.html)

The highly trained experts can assess your needs and determine the
most appropriate accommodations.  The teaching staff will follow the
instructions of these experts.  The teaching staff is not trained to
handle students with special needs.

REQUEST SPECIFIC GRADE
======================

In exceptionally rare situations, a student can request a specific
grade, regardless of the student's actual performance. Please fill
this form
(https://github.com/PurdueECE264/2020FallProblems-Lu/blob/master/GradeRequest.pdf)
and send to the instructor electronically (to email yunglu@purdue.edu)
before 2020/11/30.  This exceptional accommodation is available only
when Dr. Yung-Hsiang Lu is the instructor.

EMERGENCY
=========

If you have emergency, please dial 911.

ECE 264 is class, not emergency service.  The teaching staff will
*NOT* answer any question marked "Emergency" or "Urgent". Some
students send late assignments to the instructors and mark the subject
as "EMERGENCY". Such emails will always be ignored.

Campus Emergency
================

In case of campus emergency, please dial 911 and move the a safe place
as soon as possible. Use your judgment.  Send messages to inform your
family or friends about where you are and what you need.  Here are a
few possible scenarios of campus emergency:

* Natural Disaster: FEMA has suggestions (https://www.ready.gov/campus) about how to plan for disasters in advance.

* Outbreak of infectious diseases: Follow Purdue University's Announcements (https://protect.purdue.edu/).

* Active Shooting: FBI provide resources
  (https://www.fbi.gov/about/partnerships/office-of-partner-engagement/active-shooter-resources)
  about how to respond to the situation of active shooting.

Build Your Professional Network
===============================

ECE 264 is a large class (more than 300 students). Your classmates are
great resources.  Make as many friends as you can.

Your professional network can contribute to a more successful
career. You are welcome to join a Linkedin group for current and
former students of ECE 264 (https://www.linkedin.com/groups/8672695/).
You are encouraged to talk to alumni and learn their experience. Many
students obtain intern or regular positions through their professional
networks.

