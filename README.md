# Hello-Assembely
Hello World assembly code on 64bit Linux system 

Required OS and applications:

Linux 64bit (Not aarch64)

nasm compiler

binutils package

To assemble and run:

nasm -felf64 hello.asm && ld hello.o && ./a.out
