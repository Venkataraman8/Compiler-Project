# Compiler-Project
yacc -d c_AST.y
lex c_tokens.l
gcc lex.yy.c y.tab.c -o a.out
./a.out < test1.txt

yacc -d c_ICG.y
lex c_tokens.l
gcc lex.yy.c y.tab.c -o a.out
./a.out < test1.txt
