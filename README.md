Ceva în limbaj de asamblare
===========================

Ca să rulați programul, aveți nevoie de nasm și linux (Debian)

```
	sudo aptitude install nasm
	# pentru 64 biti forlositi elf64, elf pentru 32
	nasm -f elf64 secret.asm
	ld -o secret secret.o
	./secret
```

