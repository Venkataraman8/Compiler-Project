## Introduction
This project aims to simulate the front end phase of a C compiler involving do-while and switch case constructs. 


# Compiler-Project
yacc -d c_AST1.y <br>
lex c_tokens1.l <br>
gcc lex.yy.c y.tab.c -o a.out <br>
./a.out < test11.txt <br>

yacc -d c_ICG1.y <br>
lex c_tokens1.l <br>
gcc lex.yy.c y.tab.c -o a.out <br>
./a.out < test11.txt <br>
