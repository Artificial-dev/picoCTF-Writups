# Matryoshka dolls

## Overview
- Points: 30
- Category:  **[Forensics](/Forensics)**
- Tags: #picoCTF 2021 #Forensics

## Description

-Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What’s the final one? Image: this

## Solution

Detailed walkthrough of the steps taken to solve the challenge. Can include:


- Skills/tools/techniques - Stenography/File carving
- Approach<br>
 Starting with research on steganography and hex editors, I followed a YouTube tutorial and found a useful write-up. I came across "stegoVeritas," a tool on GitHub for steganography analysis. Using it with the command
```
kali@root# stegoveritas -carve dolls.jpg         -carve Attempt to carve/extract things from this file 
```
 I uncovered a series of images. Ultimately, I reached "4_c.jpg," revealing a hidden "flag.txt" file.


 


## Reffernce
https://medium.com/@arthDetroja/picoctf-write-up-matryoshka-doll-dd21c2b53a3d
https://github.com/bannsec/stegoVeritas.git

- Learn more About [Stenograhy](https://ctfs.github.io/resources/topics/steganography/README.html)
  
- Hex-editors
  

  [Vim](https://www.vim.org/)<br>
  [010 Editor](https://www.sweetscape.com/010editor/)<br>
  [HxD (only for windows)](https://mh-nexus.de/en/hxd/)
