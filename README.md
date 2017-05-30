Thread-Affinity-in-Java
=======================

It is a Java application that creates as many threads as there are cores and makes each thread
having scheduling affinity to a unique core.
Implementation was carried out using JNA, Java and C compilers. 
JNA was used to call native code which sets or gets the priority as needed. 
Threads were created and the processor number was passed as arguments.

The application was tested by creating a multithreaded program and factorial computation program such that thread "i" runs on core "i" and computes factorial of "i+1
