# C++11 stdlib thread/atomics tests
Playing around with standard libary threads and atomics, including memory ordering.

Mainly used for me to understand standard low level atomics, instead of custom solutions.

Just playing around with C++ <thread <atomics> stuff.
Couldn't come up with an example, therefore took one of an C++ Interview, where you have to read a file 
and parallel count how often a word exists in the whole file.

Currently created a basic Producer Consumer with mutex locking and condition variables.
I'll want to change it to lockfree by adding slots per consumer and maybe optimize it even more.
This is just testing for me to get familiar with the std threading library.
