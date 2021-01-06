---
layout: post
title: Approaching Reverse Engineering as a Total Beginner
---

(Approaching from someone with an understanding of assembly but no experience in reverse-engineering challenges)

Currently looking at the easier challenges from hackthebox to get a feel for what I'm in for. There's a lot (and I do mean _a lot_) of CTF challenges on the web- I might at some point just compile all the ones that I've heard about here later for ease of access.

The BabyRE one is from 2019 and fairly simple, but it does say that there's 4 ways to do it. I'm currently using a Windows 10 OS (yeah, yeah, it sucks but a lot of software I use is reliant on Windows and using an emulator would slow down things I need) but using a VM for the challenge because I'm more familiar with the Linux command line.

Linux P7zip to unzip the file,
Strings command,
insert found key,
then change the  execution permission of the new file that appears
execute the file,
get key.

Out of curiousity, there's 3 other ways. Let's try and find them!