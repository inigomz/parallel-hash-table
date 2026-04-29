README - CS351 Assignment 3

Language: C++

How to Execute:
1. Compile using make command:
   make

2. Start the server (in one terminal):
   ./server namesDB.txt <number of threads>
   Example: ./server namesDB.txt 10

3. Start the client (in a separate terminal):
   ./client

4. To stop the server press Ctrl+C
   This will automatically remove the message queue.

Note: If message queue is not cleaned up properly, run:
   ipcs
   ipcrm -q <queue id shown by ipcs>

Team Members:
  * Inigo: 
  * Anchal:
  * Kevin Qi: kevinJp6526@csu.fullerton.edu
  * Sola Lhim: pooloom069@csu.fullerton.edu

Extra Credit: Not implemented

# Notes
* You can not merge by yourself. There is a ruleset active that makes you 
  unable to merge by yourself. You need approval from another group member 
  before the merge is pushed to main. This is done to promote good coding 
  practices and helps avoid merge conflicts.
* In order to avoid merge conflicts as much as we can, update this makefile 
  so we know who is working on what. Always commit frequently.
