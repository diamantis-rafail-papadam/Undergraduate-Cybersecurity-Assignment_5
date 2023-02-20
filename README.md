# Technical University of Crete - HPY414 - Assignment 5
This is an assignment I completed as an undergraduate student in Technical University of Crete.

In the "exploitation.zip" file, you will find the "bof" executable, my python buffer overflow exploit, along with a README file and some screenshots to help with the understanding of how the exploit works.

Once I was able to control the instruction pointer, I redirected the program to a location in memory where I had both write and execute privileges, enabling me to place and run custom shellcode there.

If you want to try this yourself you shall put the "exploit.py", "Makefile" and "pwn.c" in the same folder and proceed with the following steps:
- Run "make", to create the "bof" executable.
- Make sure you have python 3 installed and run "(python3 exploit.py; cat) | ./bof".
- Congratulations, you now have a shellcode!
