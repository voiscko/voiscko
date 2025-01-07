![joined](https://img.shields.io/badge/joined-2022-blue)  ![Active 2025](https://img.shields.io/badge/new_start-2025-red)  ![Flipper Zero Content](https://img.shields.io/badge/Flipper_Zero_Content-ACTIVE-green)
# voiscko

## About Me
German Freelance Developer.
Contact me here: https://t.me/voiscko

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
    int 0x80
```

```asm
OS       : Win11 / Arch Linux
Languages: C++, C#, Py
Editor   : VS – bugs retire. VS Code – saves code!
Debugging: Bit by bit, step by step
Motto    : 8 Bytes are 1 Bit.
```
