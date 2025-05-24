# RobotCrackme
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

RobotCrackme is a solid mid-level crackme made in C, aimed at reversers who have already grasped the basic concepts of reverse engineering like unpacking and anti-debugging.

# The storyline

In the crackme, you need to help "Bob the Robot" find his lost passcode, so that he could change his dying battery slot. Like my previous crackme, it adds ASCII art to make the cracking process more interesting and engaging.

![robotcrackme](https://github.com/user-attachments/assets/38a4238c-c223-4ca5-87f0-e6e417aaafb4)

# Protections

This crackme is packed using XOR with a key. This means that, in order to modify the file, you'll first have to dump its unpacked memory state with something like [ScyllaHide](https://github.com/x64dbg/ScyllaHide).

Luckily, it's very easy to unpack :)

# RobotCrackme on other platforms

Explore RobotCrackme and its solutions on [crackmes.one](https://crackmes.one/crackme/67f003b88274f31a64b93762) and [crackmy.app](https://crackmy.app/crackmes/robot-crackme-7502).

