---
layout: post
title: Unix parentheses in commands docs, command(number) 
date: 2020-12-24 14:51:00

---
## Explanation

So, super quick post, it's christmas eve and I just finished the the last post 
in the logbook, it's been one of the most intresting ones. I was doing that 
when a question came to my head, what are all the numbers in perentheses when 
you look up a command. Well, I found the answer [here][stack] 

So thank you Jeroen :), I'll literaly will paste his answer here and add 
some descriptions.

It's the section that the man page for the command is assigned to.

These are split as

1. General commands: programs intended to be invoked directly by user.
2. System calls: entries into the UNIX supervisor
3. C library functions: assortment of subroutines
4. Special files (usually devices, those found in /dev) and drivers
5. File formats and conventions
6. Games and screensavers
7. Miscellanea
8. System administration commands and daemons: not intended for use by the 
ordinary user

Original descriptions of each section can be seen in the 
[Unix Programmer's Manual (page ii)][unix].

Thanks for reading :)
[unix]: https://web.archive.org/web/20170601064537/http://plan9.bell-labs.com/7thEdMan/v7vol1.pdf
[stack]: https://stackoverflow.com/questions/62936/what-does-the-number-in-parentheses-shown-after-unix-command-names-in-manpages-m
