+++
title = "Table of Content"
date = "2026-05-27T13:49:37+02:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = "Elouan DA COSTA PEIXOTO"
authorTwitter = "" #do not include @
cover = ""
description = "How to build your OWN embedded kernel from scratch in Rust and RISC-V"
showFullContent = false
readingTime = true
hideComments = false
draft = false

+++

## Introduction

When I started in computer science, the first thing I really fell in love with was operating systems. Especially kernels, I have built multiple kernels following great tutorials ([Stephen Marz: Blog](https://osblog.stephenmarz.com/index.html), [Writing an OS in Rust](https://os.phil-opp.com), ). But when I graduated from my school, I asked myself: “What do I want to do?”.I want to go into research. So I started reading the state of the art about operating systems. That’s when I learned that there’s GPOS and RTOS. I dig into industrial RTOS, especially FreeRTOS and Zephyr. And after learning things about FreeRTOS and Zephyr, I asked myself some design and architecture questions. But I didn’t have real experience in kernel development, except for those great tutorials. So I couldn’t like, know if those questions were good or if I just didn’t know anything about why it was made like that. So, for me, the best thing to do to learn something, is to build it. So I started working on my own kernel. And I’ve encountered a LOT of problems, problems I had a hard time fixing. So I told myself, when I reach a certain milestone, I’ll start working on a tutorial to write your OWN personal embedded kernel.

And how will I do that? By giving all information, notions, and all the things I learned that make a kernel work. And by not giving any code snippet. Code snippet is permitted only to illustrate syntax or notation, never to convey reasoning or architecture.

So the goal is, that you implement everything yourself. Do not use any LLM, you’ll lose the tutorial goal. And I’ll try to explain everything as best as I can. So you’ll not have too many problems implementing everything by yourself.

By the end of this tutorial, you will have a lot of knowledge of how a kernel works and how to implement those notions yourself.

So here is everything we will do:

- [Chapter 1: CPU privilege mode and binary file.](/Write-your-OWN-embedded-kernel/chapters/01/)
- [Chapter 2: RISC-V ISA.](/Write-your-OWN-embedded-kernel/chapters/02/)
- [Chapter 3: Bootloader and loading our binary in memory](/Write-your-OWN-embedded-kernel/chapters/03/).
- [Chapter 4: Kernel entry point and first step boot process](/Write-your-OWN-embedded-kernel/chapters/04/)
- [Chapter 5: Interruptions and exceptions](/Write-your-OWN-embedded-kernel/chapters/05/)
- Chapter 6: Handling memory.
- Chapter 7: What's a task?
- Chapter 8: Context switch.
- Chapter 9: Scheduling task.
- Chapter 10: Task routine and sub-routine.
- Chapter 11: Adding data structure and other primitives.
- Chapter 12: Make it work on real metal.
- Epilogue ?? Or what's next ?

If you want to check out the kernel I'm working on: <https://codeberg.org/Luernn/AldecaldOS>
