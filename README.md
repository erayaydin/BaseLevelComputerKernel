# BaLeCoK

https://kernel.live

A vucking computer kernel developed in base level.

## Compiling

You need x86_64-elf-gcc. If you are arch linux user you can get it from [AUR](https://aur.archlinux.org/packages/x86_64-elf-gcc/).

Then you need GNU Make tool.

```
$ cd BaseLevelComputerKernel
$ make
```

that gives balecok.iso as output, if you want run kernel (on bochs) you need bochs emulator. If you are arch user you cen get it from [AUR](https://aur.archlinux.org/packages/bochs-gdb/)

```
$ make bochs
```
