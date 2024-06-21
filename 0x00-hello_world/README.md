1-compiler: Compiler A script that compiles a C file but does not link. The C file name will be saved in the variable $CFILE; The output file should be named the same as the C file, but with the extension .o instead of .c;

Example: if the C file is main.c, the output file should be main.o using gcc -c $CFILE.

2-assembler: Assembler A script that generates the assembly code of a C code and save it in an output file. The C file name will be saved in the variable $CFILE; The output file should be named the same as the C file, but with the extension .s instead of .c.

Example: if the C file is main.c, the output file should be main.s using gcc -S $CFILE.

3-name: Name A script that compiles a C file and creates an executable named cisfun. The C file name will be saved in the variable $CFILE using gcc $CFILE -o cisfun.

4-puts.c: Hello, puts A C program that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.. Use the function puts; You are not allowed to use printf; Your program should end with the value 0 using:

int main(void) { puts("Programming is like building a multilingual puzzle\n"); return (0); }

5-printf.c: Hello, printf A C program that prints exactly with proper grammar, but the outcome is a piece of art,, followed by a new line. Use the function printf; You are not allowed to use the function puts; Your program should return 0; Your program should compile without warning when using the -Wall gcc option using:
