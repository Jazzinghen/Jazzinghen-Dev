---
permalink: /projects/development
title: Developmen
toc: true
toc_icon: "laptop-code"
---

## Advent of Code

![alt text](/assets/images/AoC_2021.png "Screenshot of the calendar of Advent of Code, 2021 edition")

Every year, in December, [Eric Wastl][1] organizes [Advent of Code][2], an
Advent calendar of programming puzzles of increasing difficulty that are super
useful to learn a new language, brush your skills, or just for fun.

I have participated to the following years:

- 2021
- 2022

You can find my solutions in their [git repository][3]

## Mojiharau (文字祓う)

A [mojibake'd][10] zip files fixer written in Rust. I sometimes encounter files
with wrong encoding and they inflate to files with garbage filenames. Since the
tool I found, [Mojibake Fixer][11], does what I needed but only through web
pages, I decided to reimlement it as a CLI application, allowing me to script
it.

You can find it in its [git repository][4]

## Ghidra-dark

I started using [Ghidra][12] as part of my capture-the-flag/reverse-engineering
set of tools and I was annoyed by the lack of a dark theme. After searching the
web I came across a [Dark theme injector][13], that changed the theme, but not
really in a way I liked. That's wny I forked it and updated its implementation
to use `RGBA` codes to configure colors and use [FlatLaf's][14] IntelliJ themes.

You can find the code in its [git repository][5]

## Microcorruption

I have been doing coding challenges for a long time, but during 2022 I started
diving into the capture-the-flag/reverse-engineering challenges, as I have
always been interested in reverse-engineering, and I was suggested to start with
[Microcorruption][6]. The site presents increasingly complex implementations of
a "smart" lock based on a [TI MSP430 microcontroller][15] and the user is asked to find
a way to unlock the lock without knowing the password.

These challenges forced me to learn from direct experience how multiple
low-level attacks work and how to use them.

I am currently at level "Novosibirsk".

## RustyProbe

While tackling the challenges in Microcorruption I came across a problem that
required me to disassemble some binary code that was "generated" at runtime.
After trying Microcorruption's integrated disassembler (and due to an error in
its use, I found later) I started looking for a local disassembler that helped
me read MSP430 binary code.

After finding multiple applications that I couldn't run or had other issues I
decided to implement an MSP430 disassembler in Rust, called [RustyProbe][7].

It was a fun experience, really!

## pwn.college

As I found out that I needed more skills for capture-the-flag challenges than
just assembly reverse-engineering I looked for that type of challenges for
beginners and came across [pwn.college][8], a college course by the
[Arizona State University][16] dressed up like multiple capture-the-flag
challenges.

pwn.college taught me about privilege escalation, jailbreaking, developing in
assembly (e.g. a multithreaded web server), network interception, and much more.

## Over the wire

[Over the Wire][9] is a collection of "Wargames" of increasing difficulty that
require multiple different skills in security engineering to solve.

It's a cool project handled by the community and, if I understood correctly, has
a long history.

[1]: http://was.tl/
[2]: https://adventofcode.com
[3]: https://github.com/Jazzinghen/AdventOfCode
[4]: https://github.com/Jazzinghen/mojiharau
[5]: https://github.com/Jazzinghen/ghidra-dark
[6]: https://microcorruption.com/progress
[7]: https://github.com/Jazzinghen/RustyProbe
[8]: https://dojo.pwn.college
[9]: https://overthewire.org
[10]: https://en.wikipedia.org/wiki/Mojibake
[11]: https://github.com/ianharmon/mojibake-fixer
[12]: https://ghidra-sre.org/
[13]: https://github.com/zackelia/ghidra-dark
[14]: https://www.formdev.com/flatlaf/
[15]: https://en.wikipedia.org/wiki/TI_MSP430
[16]: https://www.asu.edu/
