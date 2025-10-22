# CSC385-Week07
Producer Consumer Problem

--Overview--
This program simulates the producer-consumer problem using POSIX mutex and semaphores in C
programming language. 

It is divided into two parts, corresponding to the stages of the assignment:
  1. prod-cons.c - implements producer thread alternating between sleeping for a random period of
     time and inserting a random integer into the buffer. Random numbers are produced using the
     rand() function, which produces random integers between 0 and RAND MAX. Additionally, the
     consumer thread sleeps for a random period of time and, upon awakening, attempts to remove
     an item from the buffer.

  2. rand-prod-cons.c - Revises the code to create producers/consumers in a random fashion (a
     total of 5 consumers and 5 producers created at the end).

Both programs demonstrate synchronization to coordinate access to a shared bounded buffer among
multiple threads.

--Source Files--
prod-cons.c
rand-prod.cons.c
