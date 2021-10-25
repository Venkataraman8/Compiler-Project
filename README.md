# Compiler-Project
yacc -d c_AST.y <br>
lex c_tokens.l <br>
gcc lex.yy.c y.tab.c -o a.out <br>
./a.out < test1.txt <br>

yacc -d c_ICG.y <br>
lex c_tokens.l <br>
gcc lex.yy.c y.tab.c -o a.out <br>
./a.out < test1.txt <br>
