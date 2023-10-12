## asm_sum

```
nasm -f elf convert.asm -o convert.o
```

```
ld convert.o -m elf_i386 -s -o convert
```

```
./convert
```
