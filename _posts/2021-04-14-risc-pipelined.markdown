---
title: "IITB RISC Pipelined"
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

# IITB RISC Pipelined
Check the github repository here: [IITB RISC Pipelined](https://github.com/kalpitborkar/IITB-RISC-Pipelined)

# What is IITB-RISC?
IITB-RISC is a 16-bit very simple computer developed for the teaching that is based on the Little Computer Architecture.
The IITB-RISC-22 is a 16-bit computer system with 8 registers.
It follows the standard 6 stage pipeline:
  1. Instruction fetch
  2. Instruction decode
  3. Register read
  4. Execute
  5. Memory access
  6. Write back
 
The architecture is optimized for performance using hazard mitigation techniques namely:
  1. Forwarding
  2. Branch prediction