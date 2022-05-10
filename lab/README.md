# Lab Assignments

This page contains a complete set of turnkey labs for the CS:APP3e text. The labs all share some [common features](http://csapp.cs.cmu.edu/3e/labinfo.html). Each lab is distributed in a self-contained tar file. You will need a [CS:APP account](http://csapp.cs.cmu.edu/3e/loginrequest.html) to download the code. To untar foo.tar, type "tar xvf foo.tar" to the Unix shell. This will create a directory called "foo" that contains all of the material for the lab.

Handout directories for each lab (without solutions) are available to students who are using the book for self-study and who want to work on the labs. Solutions are provided only to instructors.

·  [*Data Lab*](http://csapp.cs.cmu.edu/im/labs/datalab.tar) ***[Updated 12/16/19]\*** ([README](http://csapp.cs.cmu.edu/3e/README-datalab), [Writeup](http://csapp.cs.cmu.edu/3e/datalab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/datalab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/datalab-handout.tar)) ![[NEW]](file:///C:/Users/Westo/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)

Students implement simple logical, two's complement, and floating point functions, but using a highly restricted subset of C. For example, they might be asked to compute the absolute value of a number using only bit-level operations and straightline code. This lab helps students understand the bit-level representations of C data types and the bit-level behavior of the operations on data.

·  [*Bomb Lab*](http://csapp.cs.cmu.edu/im/labs/bomblab.tar) *[Updated 1/12/16]* ([README](http://csapp.cs.cmu.edu/3e/README-bomblab), [Writeup](http://csapp.cs.cmu.edu/3e/bomblab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/bomblab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/bomb.tar))

A "binary bomb" is a program provided to students as an object code file. When run, it prompts the user to type in 6 different strings. If any of these is incorrect, the bomb "explodes," printing an error message and logging the event on a grading server. Students must "defuse" their own unique bomb by disassembling and reverse engineering the program to determine what the 6 strings should be. The lab teaches students to understand assembly language, and also forces them to learn how to use a debugger. It's also great fun. A legendary lab among the CMU undergrads.

Here's a [Linux/x86-64 binary bomb](http://csapp.cs.cmu.edu/3e/bomb.tar) that you can try out for yourself. The feature that notifies the grading server has been disabled, so feel free to explode this bomb with impunity. If you're an instructor with a CS:APP account, then you can download the [solution](http://csapp.cs.cmu.edu/im/bomb-solution.txt).

·  [*Attack Lab*](http://csapp.cs.cmu.edu/im/labs/attacklab.tar) ***[Updated 1/11/16]\*** ([README](http://csapp.cs.cmu.edu/3e/README-attacklab), [Writeup](http://csapp.cs.cmu.edu/3e/attacklab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/attacklab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/target1.tar))

*Note: This is the 64-bit successor to the 32-bit Buffer Lab.* Students are given a pair of unique custom-generated x86-64 binary executables, called *targets*, that have buffer overflow bugs. One target is vulnerable to code injection attacks. The other is vulnerable to return-oriented programming attacks. Students are asked to modify the behavior of the targets by developing exploits based on either code injection or return-oriented programming. This lab teaches the students about the stack discipline and teaches them about the danger of writing code that is vulnerable to buffer overflow attacks.

If you're a self-study student, here are a pair of [Ubuntu 12.4 targets](http://csapp.cs.cmu.edu/3e/target1.tar) that you can try out for yourself. You'll need to run your targets using the **"-q"** option so that they don't try to contact a non-existent grading server. If you're an instructor with a CS:APP acount, you can download the solutions [here](http://csapp.cs.cmu.edu/im/labs/target1-sol.tar).

·  [*Buffer Lab (IA32)*](http://csapp.cs.cmu.edu/im/labs/buflab32.tar) *[Updated 9/10/14]* ([README](http://csapp.cs.cmu.edu/3e/README-buflab32), [Writeup](http://csapp.cs.cmu.edu/3e/buflab32.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/buflab32-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/buflab32-handout.tar))

*Note: This is the legacy 32-bit lab from CS:APP2e. It has been replaced by the Attack Lab.* In the Buffer Lab, students modify the run-time behavior of a 32-bit x86 binary executable by exploiting a buffer overflow bug. This lab teaches the students about the stack discipline and teaches them about the danger of writing code that is vulnerable to buffer overflow attacks.

·  [*Architecture Lab*](http://csapp.cs.cmu.edu/im/labs/archlab.tar) ***[Updated 10/19/16]\*** ([README](http://csapp.cs.cmu.edu/3e/README-archlab), [Writeup](http://csapp.cs.cmu.edu/3e/archlab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/archlab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/archlab-handout.tar))

*Note: Updated to Y86-64 for CS:APP3e.* Students are given a small default Y86-64 array copying function and a working pipelined Y86-64 processor design that runs the copy function in some nominal number of clock cycles per array element (CPE). The students attempt to minimize the CPE by modifying both the function and the processor design. This gives the students a deep appreciation for the interactions between hardware and software.

Note: The lab materials include the master source distribution of the Y86-64 processor simulators and the *Y86-64 Guide to Simulators*.

·  [*Architecture Lab (Y86)*](http://csapp.cs.cmu.edu/im/labs/archlab32.tar) ***[Updated 10/19/16]\*** ([README](http://csapp.cs.cmu.edu/3e/README-archlab32), [Writeup](http://csapp.cs.cmu.edu/3e/archlab32.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/archlab32-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/archlab32-handout.tar))

*Note: Legacy Y86 version for CS:APP2e.* Students are given a small default Y86 array copying function and a working pipelined Y86 processor design that runs the copy function in some nominal number of clock cycles per array element (CPE). The students attempt to minimize the CPE by modifying both the function and the processor design. This gives the students a deep appreciation for the interactions between hardware and software.

Note: The lab materials include the master source distribution of the Y86 processor simulators and the *Y86 Guide to Simulators*.

·  [*Cache Lab*](http://csapp.cs.cmu.edu/im/labs/cachelab.tar) **[Updated 5/2/16]** ([README](http://csapp.cs.cmu.edu/3e/README-cachelab), [Writeup](http://csapp.cs.cmu.edu/3e/cachelab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/cachelab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/cachelab-handout.tar))

At CMU we use this lab in place of the Performance Lab. Students write a general-purpose cache simulator, and then optimize a small matrix transpose kernel to minimize the number of misses on a simulated cache. This lab uses the Valgrind tool to generate address traces.

Note: This lab must be run on a 64-bit x86-64 system.

·  [*Performance Lab*](http://csapp.cs.cmu.edu/im/labs/perflab.tar) *[Updated 9/2/14]* ([README](http://csapp.cs.cmu.edu/3e/README-perflab), [Writeup](http://csapp.cs.cmu.edu/3e/perflab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/perflab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/perflab-handout.tar))

Students optimize the performance of an application kernel function such as convolution or matrix transposition. This lab provides a clear demonstration of the properties of cache memories and gives them experience with low-level program optimization.

·  [*Shell Lab*](http://csapp.cs.cmu.edu/im/labs/shlab.tar) *[Updated 7/28/03]* ([README](http://csapp.cs.cmu.edu/3e/README-shlab), [Writeup](http://csapp.cs.cmu.edu/3e/shlab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/shlab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/shlab-handout.tar))

Students implement their own simple Unix shell program with job control, including the ctrl-c and ctrl-z keystrokes, fg, bg, and jobs commands. This is the students' first introduction to application level concurrency, and gives them a clear idea of Unix process control, signals, and signal handling.

·  [*Malloc Lab*](http://csapp.cs.cmu.edu/im/labs/malloclab.tar) *[Updated 9/2/14]* ([README](http://csapp.cs.cmu.edu/3e/README-malloclab), [Writeup](http://csapp.cs.cmu.edu/3e/malloclab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/malloclab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/malloclab-handout.tar))

Students implement their own versions of malloc, free, and realloc. This lab gives students a clear understanding of data layout and organization, and requires them to evaluate different trade-offs between space and time efficiency. One of our favorite labs. When students finish this one, they really understand pointers!

·  [*Proxy Lab*](http://csapp.cs.cmu.edu/im/labs/proxylab.tar) ***[Updated 11/14/19]\*** ([README](http://csapp.cs.cmu.edu/3e/README-proxylab), [Writeup](http://csapp.cs.cmu.edu/3e/proxylab.pdf), [Release Notes](http://csapp.cs.cmu.edu/3e/proxylab-release.html), [Self-Study Handout](http://csapp.cs.cmu.edu/3e/proxylab-handout.tar)) ![[NEW]](file:///C:/Users/Westo/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif)

Students implement a concurrent caching Web proxy that sits between their browser and the rest of the World Wide Web. This lab exposes students to the interesting world of network programming, and ties together many of the concepts from the course, such as byte ordering, caching, process control, signals, signal handling, file I/O, concurrency, and synchronization.