## Week - 1 Day 2

### Hardware
What is a computer?
*Memory, RAM
*CPU (processor)
**Inputs - keyboard, mouuse
**Output - monitor
**GPU
**Networking

*programming is done in memory and the CPU
**These are part of the OS

CPU is a fancy calculator and memory manipulator

### How to make CPU do those things?
    - Electrical signals
        organised by machine code
            least human friendly
        Programming language "high level"
    The compiler takes the highlevel language and turns it into machine code
        eg C++ (language), clang (compiler)

Comments are notes for programmers, ignored by compilers
    // in C++
        /* multiline comment*/
We need to write software knowing that humans will be reading our code

Guts of C++ Programme:

```
    #include (iostream) //iostream is a library
    int main() { <these are some code instructions>
        }
```

### Errors
You will screw up. We all screw up. This *will* happen.
Types of error:
    Syntax error
        The easiest to fix and detect
            eg "I is good"
    Run time error
        more difficult
            biggest and most dangerous is a logic error
                logic error: the instructions you gave don't do what you wanted, but are valid
    Linker error
        sort of in-between

### Memory
RAM - random access memory
    We can grab whatever pieces of this and that we want when we want
        All electrical
            Hardrives are harder because there are physical locations that must be found and then accessed
    
    Ram is a collection of bytes
        a byte is 8 bits
            a bit is a 0 or a 1
        A byte stores one character of latin text
            ie a character of latin texts is 8 bits

    RAM is like a table with numbers from 0 to huge number
 Useful table:

Name
Type
Value

Name                    Type                        Value
User age               int/float                   23/23.5
School Address     string, “address”   “2020 s campus drive blah blah blah"
Temp in C              float                        24.3
       
each row is a variable

### Data types
int
    int, long, short
float, double
    float is 4 bytes, double is 8
Boolean
    true/false
Char
    one character
        'use single quotes'
string
    text
        "use double quotes"

### Vars in C++
first, we want to reserve space in RAM
“Variable declaration"
Int userAge;
Float tempInC;
Bool isStudent;
String name;

“Assignment” ‘=‘ is like a left arrow
    Take the thing on the right, and store it in the variable on the left

var = value
isStudent = true;

"use value"
just write its name

***declare, assign, write out***

Mixing:
Int x = 0;
     Mixed declaration and assignment
Y = x+3
    Assignment (=) and get value
Int z = x+y
    D, A, GV

% “modulo” - remainder after division
 What is left over
     Eg: 5%3 = 2
         Because 3 goes into 5 one time with a remainder of 2

5/3 =/= 1.666
    5/3 == 1
        Because when you use integers, you get back integers
5.0 / 3 == 1.66666

### Operating System
I/O
C++
 cout
     Std :: cout <<what
             << to
             << print;
     Std :: cout << x;
     Std :: cout x << x << std :: endl;
        * //endl == end line
 Int x;
 Float f;
 Cin
     Std :: cin >>x >> f;


### Shorthand maths
Y = y + x —— y + = x
x = x +1 —— x + =1
f = f + 2 —— f * = 2
x + = 1 —— x ++ or + + x (Where C++ gets its name. C++ is 1 better than C)
x - = 1 —— x - - or - - x