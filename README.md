# Section 1. General introduction

## 1.1 Computers and programming languages

1\.    Hardware: processors, memory, caches, disks and the like...

2\.    Operating system: “system software that manages computer hardware and software resources and provides common services for computer programs.\[... \] For hardware functions such as input/output and memory allocation, the operating system acts as an intermediary between programs and the computer hardware” (Wikipedia). Operating system interacts with file system, launches other programs assigning resources to them, interacts with the user, detects events (movement of the mouse, clicks, pressing a key, etc.).

On desktop computers, the dominant operating system is Microsoft Windows, followed by Apple's macOS and various distributions of Linux. On smartphones and tablets, Google's Android is the leader, followed by Apple's iOS. Linux distributions are dominant in the server and super-computing sectors.

According to Stack Overflow, among professional developers 50% uses Windows, 27% uses macOS and 23% a Linux distribution.

3\.    Bits and bytes, hexadecimal and octal system.

* Bit: — the smallest unit of information; only two values possible (0 or 1, ‘up’ or ‘down’, ‘black’ or ‘white’,...). By convention, we use 0 and 1 picture, because it allows us to interpret sequences of bits as numbers in the binary system.

* Byte: — a sequence of 8 bits. There are 28 = 256 such sequences possible; interpreted as numbers in the binary system, they assume values in the closed interval \[0, 255\].

* hexadecimal notation: — very practical, because four bits can be in exactly 2[1](#bookmark2) = 16 combinations, so there is a one-to-one correspondence between any sequence of four bits and a single digit in hexadecimal notation (0-9, A, B, C, D, E, F — hex-digits A-F can also be written in lowercase). It follows that there is a one-to-one correspondence between all possible bytes and all sequences of exactly two hex-digits. For example 255<sub>10</sub> = 11111111<sub>2</sub> = FF<sub>16</sub> and 46<sub>10</sub> = 00101110<sub>2</sub> = 2E<sub>16</sub>.

4\.    Processor: — is what ‘does the job’ in the computer. Important components of a processor are registers — information, in the form of sequences of bits, can be stored there and manipulated by **instructions**, which themselves are also expressed as sequences of bits. There is a limited number of instructions that any given processor ‘understands’ (its **instruction set**). These are elementary instructions, like ‘set a register X to a value’, ‘copy data from a memory location M to the register Y’ (or vice versa), ‘add (subtract, multiply, divide) the values of two registers, X and Y, and place the result in register Z’, and so on. It is important to realize that no matter what programming language we use, our program must be ultimately somehow transformed into the form of a long sequence of these simple, elementary instructions (i.e., into the form of the **machine code** or **executable**).

5\.    Program: — a sequence of instructions (perhaps from many source files) in any language which, after transforming into machine code, performs an indicated task.

6\.    Compiler: — a program which reads one or more source files (just text files) and transforms them into machine code which can then be passed to the processor. Sometimes the result is not an executable, but has some intermediate form, which is then compiled ‘to the end’ and passed to the processor by another, additional, program. This, for example, is the case for Java, as we will see. Some languages are not compiled — there is a program, called interpreter, which reads the source file line by line and transforms it into machine code ‘on the fly’ in memory, without creating separate executable files (this is the case, for example, for the Python programming language).

7\.    Programming languages:

* Low-level: machine code, assembly language.

* High-level: interpreted or compiled. There are many attempts to categorize languages, but it seems not to be possible to do it. Broadly speaking, we can divide languages into categories like

    — imperative: procedural, object-oriented;

    — declarative: relational, functional, logic.

Currently, the most popular programming languages are Java, C/C++, Python and Java Script. On the other hand, popularity of languages depends on the subject domain; for scientific and engineering calculations, the Fortran and Mathe-matica programming languages would be closer to the top of this list, while for statistical applications the language called R is extremely useful and popular.

8\.    Algorithm: — “an unambiguous specification of how to solve a class of problems” (Wikipedia). Therefore, an algorithm is a kind of a recipe which tells us how to obtain the result we want in finite number of steps. For example: given a collection of, say, 3 million, numbers, how to sort them in ascending order? Or, given two whole positive numbers, how to find their greatest common divisor (there is a famous solution of this problem given by Euclid in his _Elements_). Generally, when writing a program or a part of it, what we have to consider first is just an algorithm which should be used to achieve our goal correctly and efficiently.

The word _algorithm_ has been derived from the name of a IX century Persian scholar Muhammad ibn Musa al-KhwarizmT and Greek word apifipóę (which means number). \[By the way, the term _algebra_ comes form the Arabic word _al-jabr_, appearing in the title of al-Khwarizmi’s main work.\]

## 1.2 What is Java?

Java — high level imperative programming language, object-oriented with some elements of functional programming. In the design of Java, emphasis has been put on

3\.    Executed by (platform dependent) JVM — Java Virtual Machine, which interprets byte code, transforms it into machine code (dynamically, without storing it on disk) which is passed to the processor(s).

4\.    Simple syntax very close to that of C/C++.

5\.    Built-in (in the form of a platform independent standardized library):

*   graphics (building GUIs — graphical user interfaces);

*   multithreading (concurrency); ;

*   network programming;

*   working with data bases;

*   multimedia (processing images, sound);

*   support for various security issues;

*   support for microprogramming — for ‘small’ devices, mobile phones, etc.

*   handling various data formats, like XML, JSON, etc.;

*   ... and much, much more...

## Installation: 

Oracle web [page](#bookmark6)[2](#bookmark7) — install something called JDK (Java Development Kit). It installs the JVM (allowing to run Java programs) but also various tools which allow the developer to create Java programs (in particular, the compiler). Documentation — as one big zip file — can also be downloaded, or it can be viewed [online](#bookmark8)[3](#bookmark9).

Section 2 -

[1](#footnote1)

   efficiency;

[2](#footnote2)

[https://www.oracle.com/technetwork/java/javase/downloads/index.html](https://www.oracle.com/technetwork/java/javase/downloads/index.html)

[3](#footnote3)

[https://docs.oracle.com/en/java/javase/21/docs/api/java.base/module-summary.html](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/module-summary.html)
