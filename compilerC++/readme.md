Name : Ankush Naskar
Entry No. : 2022CSB1068

To Run:
 lex cucu.l
 yacc -d cucu.y -o cucu.tab.c
 cc lex.yy.c cucu.tab.c -o output.out -ll
 ./output.out sample2.cu

Correct Code:
    Sample 1 : ---
    Sample 2 : Code For Tower Of Hanoi

Wrong Code:
    Sample 3 : Errors in Code for Tower of Hanoi

If error in syntax is deducted,
    program throws either Segmentation Fault in Terminal Or Prints Syntax Error in Lexer.cu
If invalid character is detected, 
    program prints Invalid Character in Lexer.cu

Most C programs that satisfy below criteria should work!

Supported:
    Data Types - int, char*, char**
    Arrays []
    Strings
    If else if
    etc.

Support Not Added for:
    FOR Loops,
    Operators : ++, --, +=, -=, *=, /=
    Structs
    Multidimensional Arrays
