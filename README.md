java c
EIE2105 Digital and Computer Systems 
Tutorial 7: Microprocessor Design Basics and Instruction Set Architecture Q1.       Figure Q1a shows part of   the memory space of   an 8088 system. It is given that the current content of   registers DS,   SI, AX and BX are, respectively,   10H,   10H,   60H and EF0H.
Physical Address 
Hex data 
1000H 
01 
23 
04 
05 
09 
06 
10 
02 
1008H 
02 
10 
24 
72 
31 
00 
40 
10 
1010H 
: 
40 
51 
64 
79 
90 
A9 
C4 
E1 
2000H 
10 
11 
12 
13 
14 
15 
17 
16 
Figure   Q1a
Address 
Machine code 
Instruction 
CS:0100 
8B4802 
MOV 
CX, [BX+SI+2] 
CS:0103 
B425 
MOV 
AH, 25H 
CS:0105 
88E0 
MOV 
AL, AH 
CS:0107 
01C8 
ADD 
AX, CX 
Figure   Q1b
Trace the assembly language program segment   shown   in   Figure   Q1b.   Show   the   contents   of   registers   AX   and   CX   after   the   execution   of   each   instruction.Q2.         Explain   how   the   bus   width   of a   microprocessor’s   address   bus   and   data   bus   affects   the system performance of   a computer system.
Q3.    A   program is compiled to generate the follow   executable machine   code   sequence.
78H             56H               32H               87H               23H               98H               42H                11H               05H               …
The program is then loaded to the main memory of   an   8086-based computer   system   starting from address 5000H as   shown in   Fig.Q3   for being   executed.

Fig   Q3
Based on the available information, answer the   following   questions.
(a)   What is the logical address of   the datum   stored   in memory   location   5002H?
(b)   What is the physical address of   the datum stored   in memory   location   5003H?
(c)   What is the logical address of   the 5th   byte   of   the program   (i.e.,   23H)?
(d)   What   is   the   physical   address   of   the   5th      byte   of   the   program?
(e)   What   is   the   physical   address   of   the   5th      byte   of   the   program   before   the   program   is being loaded into the main memory?
(f)    Data A is a word in the program and it is stored   in memory locations   5006H   and   5007H, determine its value.
(g)   Compare the life cycle of   data   A’s logical address and physical   address.   Which   one   is   longer?
(h)   If   the microprocessor of   the system wants to access data   A, which   address   signal   (in   value) will be delivered through the address bus? Is it   a physical address?
Q4.    How does the X86 system know the   fetched binary pattern   is   an instruction   or   not?
Q5.    Fill in the blank with the following keywords:
[mainframe. computer]   [secondary storage]   [primary s代 写EIE2105 Digital and Computer Systems Tutorial 7: Microprocessor Design Basics and Instruction Set ArchitectureJava
代做程序编程语言torage]   [conditional branch]
[register]   [server]   [grid]   [minicomputer]   [Control unit]   [server]   [Application]   [instruction]
[registers]   [memory]   [I/O device]   [System]   [computer network]   [bus]   [cluster]   [ALU]
[programming language]   [general-purpose]   [RAM]   [operating system]
1.                A(n) ________ generally supports more simultaneous users than a(n) ________. Both are   designed to support more than   one user.
2.                A(n) __________ is a   storage location   implemented   in   the   CPU.
3.                The term _______ refers to storage devices, not located in the CPU, that hold instructions   and   data   of   currently   running   programs.
4.                A   problem-solving procedure that requires executing one or more comparison and branch   instructions is called a(n) _________.
5.                A(n) ________ is   a   command   to   the   CPU   to   perform   one   processing   function   on   one   or   more data   inputs.
6.                The term ________   describes the   collection   of storage   devices   that   hold   large   quantities   of   data for   long periods.
7.                A(n)    __________      is      a      computer      that      manages      shared      resources      and      allows      other   computers to access them through a network.
8.                The   major   components   ofa   CPU   are   the   _______, _______, and   _______.9.                Primary       storage      can      also    be       called    _______       and       is      generally      implemented      with
__________.10.          A set of   instructions that is executed to solve a specific problem is called a(n) _________.
11.          A(n) __________ is a group of   similar or identical   computers,   connected by   a high-speed network, that cooperate to provide services or run an application.
12.          A(n) ___________ is a group of   dissimilar computer   systems,   connected by   a high-speed   network, that cooperate to provide services or run a shared   application.
13.          A(n) ___________ consists of   computing resources with a Web-based front-end interface   to a large collection of   computing   and data   resources.
14.          A(n)   ___________   is   a   hardware   device   that   enables   a   computer   to   communicate   with   users or other   computers.
15.          A CPU   is   a(n) _________ processor   capable   of   performing   many   different   tasks   simply   by changing the program.
16.          The ________ is the “plumbing”   that   connects   all   computer   system   components.
17.          Most programs are   written   in   a(n)   ________,   such   as   C   or   Java,   which   is   then   translated   into equivalent CPU   instructions.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
