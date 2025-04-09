# Hobby i386 Operating System

Hobby i386 Operating System.

[:octicons-mark-github-16: GitHub Repo](https://github.com/automas-dev/os/)

[![CI Tests](https://github.com/automas-dev/os/actions/workflows/ci.yml/badge.svg){.middle}](https://github.com/automas-dev/os/actions/workflows/ci.yml)

## Project Features

1. Unit tests with mocks from fff and coverage from gcov
2. Cross compiler target i386 elf
3. GitHub Actions CI for PRs
      - Test & Lint
      - Increment Version
      - Using shared, reusable workflow
4. Qemu emulation with VSCode debugger
5. Organized project structure with division of concern

## OS Features

1. Stage 1 Boot Loader
2. Stage 2 Kernel
3. Hardware Drivers
      1. VGA
      2. Keyboard
      3. ATA
      4. RTC
      5. PIT
4. Software Drivers
      1. Tar
      2. Ramdisk
      3. Disk
5. i386 CPU
      1. Virtual Memory (paging)
      2. ISR & IDT
      3. MMU
      4. TSS
6. Multi-Task Support (Process)
      1. Independent event queue
      2. System calls via Software Interrupt 48
      3. Virtual Memory
7. LibC
