using nasm:
<br />
nasm -f elf32 problem1.asm -o problem1.o
<br />
gcc -m32 -o problem1 problem1.o

<br />
./problem1

<br />
answer: 1938424

<br />
debugging:
https://github.com/newtonsart/vscode-assembly/blob/master/README.md