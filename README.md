# Hello-Assembely
Hello World assembly code on 64bit Linux system 

Required OS and applications:

Linux x64 (Not arm64)

NASM assembler

binutils package

To assemble and run:

nasm -felf64 hello.asm && ld hello.o && ./a.out
