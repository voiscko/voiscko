![Active 2025](https://img.shields.io/badge/new_start-2025-red)
# voiscko

## About Me
French Freelance Developer.

```asm
section .data
    msg db 'voiscko', 0

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, msg
    mov edx, 7
    int 0x80

    mov eax, 1
    xor ebx, ebx
    int 0x80```

asm```

**OS**       : i3, macOS  
**Languages**: C, ASM, Py  
**Editor**   : VIM, forever and ever  
**Debugging**: Bit by bit, step by step  
**Motto**    : Seek strength. The rest will follow.
