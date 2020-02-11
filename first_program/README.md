From https://www.youtube.com/watch?v=wLXIWKUWpSs

Commands to run it:
nasm -f elf32 first.asm -o first.o
ld -m elf_i386 first.o -o first
./first
echo $?

Output:
42

It works!

