<div align="center">

<pre>
__   __   ___   ___  _____   ____   _  __   ___ 
\ \ / /  / _ \ |_ _|/ ___/  / ___| | |/ /  / _ \
 \ V /  | | | | | | \___ \ | |     | ' /  | | | |
  | |   | |_| | | |  ___) || |___  | . \  | |_| |
  |_|    \___/ |___||____/  \____| |_|\_\  \___/
</pre>

<p align="center">
  <img alt="Sys_Init" src="https://img.shields.io/badge/INIT-OK-00FF00?style=for-the-badge&color=000000&logoColor=00FF00" />
  <img alt="Mem_Check" src="https://img.shields.io/badge/MEM-ALLOCATED-00FF00?style=for-the-badge&color=000000&logoColor=00FF00" />
  <img alt="Uptime" src="https://img.shields.io/badge/UPTIME-100%25-00FF00?style=for-the-badge&color=000000&logoColor=00FF00" />
</p>

<!-- Typing SVG -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=4000&pause=1000&color=00FF00&center=true&vCenter=true&width=500&lines=root@voiscko:~%23+whoami;German+Freelance+Developer;root@voiscko:~%23+./init_system.sh;[OK]+System+operational." alt="Typing SVG" /></a>

<p align="center">
  <code><a href="https://discord.com/users/1155541621044162711" style="color:#00FF00">[ Connect via SSH/Discord ]</a></code> •
  <code><a href="https://t.me/voiscko" style="color:#00FF00">[ Ping via Telegram ]</a></code>
</p>

</div>

---

### `> cat /var/log/user_profile.log`

```text
[INFO] Loading user profile...
[USER] Name: voiscko
[ROLE] German Freelance Developer
[DESC] Always ready to solve complex problems and build cool things.
[STAT] Open for new projects and collaborations.
```

### `> ls -la /usr/local/bin/skills`

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=asm,c,cpp,python,linux,git,nodejs,vercel,supabase&theme=dark" />
  </a>
</p>

### `> tail -n 15 /boot/sys_write.asm`

```asm
section .data
    msg db 'voiscko', 0xa

section .text
    global _start

_start:
    mov eax, 4      ; sys_write
    mov ebx, 1      ; stdout
    mov ecx, msg    ; message pointer
    mov edx, 8      ; length
    int 0x80        ; syscall

    mov eax, 1      ; sys_exit
    xor ebx, ebx    ; exit status 0
    int 0x80        ; syscall
```

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=voiscko&show_icons=true&theme=terminal&hide_border=true&include_all_commits=true&count_private=true&title_color=00ff00&text_color=00ff00&icon_color=00ff00&bg_color=000000" alt="voiscko's System Stats" />
</div>
