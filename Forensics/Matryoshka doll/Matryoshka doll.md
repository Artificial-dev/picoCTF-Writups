# Challenge Name

## Overview
- Points: 30
- Category:  **[Forensics](/Forensics)**
- Tags: #picoCTF 2021 #Forensics

## Description

-Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What’s the final one? Image: this

## Solution

Detailed walkthrough of the steps taken to solve the challenge. Can include:


- Skills/tools/techniques - Stenography
Approch I Got to know about stenography and hexeditor tools by this video on youtube.Searching through writups on google , got an tool stegoVeritas which give me a new image file named 2_c.jpg then got 3, 4 and at last 4_c.jpg gaved me flag.txt
I used following commands
stegoveritas -carve dolls.jpg     -carve     Attempt to carve/extract things from this file

 


## Reffernce
https://medium.com/@arthDetroja/picoctf-write-up-matryoshka-doll-dd21c2b53a3d
https://github.com/bannsec/stegoVeritas.git
