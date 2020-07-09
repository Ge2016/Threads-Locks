JAVA:
# Threads-Locks
Programming Assignment 2 

Your task is to design and implement a set of classes that process a collection of Integer objects, corresponding to an M&M color.
The program was run with 5 threads. There are 10000 M&Ms. The number of M&Ms and portion calculated by each tabulator are printed by the class ThreadStatisticsSetup.
Each thread in the RequestProcessor class must use a lock before accessing the collection. The threads must be as concurrent as possible, within reason. 
