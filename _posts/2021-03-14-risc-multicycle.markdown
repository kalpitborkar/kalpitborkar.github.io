---
title: "IITB RISC Multicycle"
layout: post
# date: 2016-01-23 22:10
tag: jekyll
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "IITB-RISC is a 16-bit very simple computer developed for the teaching that is based on the Little Computer Architecture."
category: project
author: kalpitborkar
externalLink: false
---

# IITB-RISC Multicycle
Check the github repository here: [IITB RISC Multicycle](https://github.com/kalpitborkar/IITB-RISC-Multicycle)
# What is IITB-RISC?
- IITB-RISC is a multi-cycle processor with the Instruction Set Architecture provided [here](https://github.com/kalpitborkar/IITB-RISC-Multicycle/tree/main/Microprocessor%20Instruction%20Set%20Architecture).
- IITB-RISC is a 16-bit very simple computer developed for the teaching that is based on the Little Computer Architecture.
- The IITB-RISC-22 is a 16-bit computer system with 8 registers.

# IITB-RISC Instruction Set Architecture
- The IITB-RISC is an 8-register, 16-bit computer system.
- It has 8 general-purpose registers (R0 to R7).
- Register R7 is always stores Program Counter.
- All addresses are short word addresses (i.e., address 0 corresponds to the first two bytes of main memory, address 1 corresponds to the second two bytes of main memory, etc.).
- This architecture uses condition code register which has two flags Carry flag ( C ) and Zero flag (Z).
- There are three machine-code instruction formats (R, I, and J type) and a total of 17 instructions.