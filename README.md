<div align="center">
  
# ⚡️ voiscko

<p align="center">
  <img alt="System Init" src="https://img.shields.io/badge/System_Init-2022_CE-blue?style=for-the-badge&color=000000&logoColor=white" />
  <img alt="Reconfig Scheduled" src="https://img.shields.io/badge/Reconfig_Scheduled-2025_CE-orange?style=for-the-badge&color=000000&logoColor=white" />
  <img alt="Status" src="https://img.shields.io/badge/Status-OPERATIONAL-brightgreen?style=for-the-badge&color=000000&logoColor=white" />
</p>

<!-- Typing SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=2196F3&center=true&vCenter=true&width=435&lines=German+Freelance+Developer.;Low-Level+Enthusiast.;Crafting+elegant+solutions." alt="Typing SVG" /></a>

<p align="center">
  <a href="https://discord.com/users/1155541621044162711">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <a href="https://t.me/voiscko">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
</p>

</div>

---

### 👨‍💻 System Log

- 💻 **German Freelance Developer**
- 🔧 Always ready to solve complex problems and build cool things.
- 💬 Open for new projects and collaborations.

### 🛠️ Tech Stack & Tools

<p align="left">
  <!-- Feel free to change the icons! List of all available icons: https://github.com/tandpfun/skill-icons -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=asm,c,cpp,python,linux,git,bash,docker,vscode" />
  </a>
</p>

### ⚙️ Boot Sequence (`sys_write`)

```asm
section .data
    msg db 'voiscko', 0xa  ; Added newline for cleaner output

section .text
    global _start

_start:
    ; Write 'voiscko' to stdout
    mov eax, 4      ; sys_write
    mov ebx, 1      ; stdout
    mov ecx, msg    ; message pointer
    mov edx, 8      ; length (7 chars + newline)
    int 0x80        ; syscall

    ; Exit program gracefully
    mov eax, 1      ; sys_exit
    xor ebx, ebx    ; exit status 0
    int 0x80        ; syscall
```

---

<div align="center">
  
  <img src="https://github-readme-stats.vercel.app/api?username=voiscko&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="voiscko's GitHub Stats" />

</div>
