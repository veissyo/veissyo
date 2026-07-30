

```asm
.global _start
.data
info:
    .ascii "CS student. Low-level mind. Embedded systems enthusiast.\n"
data_len = . - info 
.text
_start:
    mov x0, #1
    ldr x1, =info
    mov x2, #data_len
    mov x8, #64
    svc #0

    mov x0, #0
    mov x8, #93
    svc #0
```
## About me
I want to write code that talks directly to the hardware. Interested in embedded systems, bare-metal programming, and the layer where software meets silicon. 

## Skills
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

## Stats 
[![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=veissyo&layout=compact&langs_count=3&theme=dark)](https://github-stats-extended.vercel.app/api/top-langs?username=anuraghazra&layout=compact&langs_count=2&theme=dark)
