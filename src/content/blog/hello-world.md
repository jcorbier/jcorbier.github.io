---
title: Hello, world!
author: Jeremie Corbier
pubDatetime: 2023-10-09T17:12:31Z
postSlug: hello-world
featured: true
draft: false
tags:
  - RandomThoughts
  - Programming
  - Memories
description:
  First post in a hopefully long series of them (hahahaha)
---

Many blogs start with a dummy post. Many programmers start learning a new
language with the well known Hello, world! Here I am going down the memory
lane, trying to remember key moments in my developer journey.

## Hello, world!

```c
#include <stdio.h>

int main(int argc, char *argv[]) {
    printf("Hello, world!\n");

    return 0;
}
```

I have been using C as my main language for decades now. My very first Hello
world dates all the way back to 1997 if I remember correctly. I recall the
frustration of setting up a compilation toolchain on the old Windows computer
my parents had reluctantly bought, not because they didn't want to but because
finances were rough back then. I have this joyful memory of me jumping up and
down when I saw these two words print on my console.

## Programming in my head

```vb
Imports System

Module Module1
  Sub Main()
    Console.WriteLine("Hello, world!")
  End Sub
End Module
```

My first contact with programming was a few years before that though. I didn't
even have a computer at home. But I was so obsessed with them that my uncle
first bought me a Visual Basic For Dummies book, then the summer after that,
brought his bulky laptop for his vacation and lent it to me for the couple of
weeks he stayed.

I didn't let go of the thing for days and sleepless nights, putting into
practice what I had read and thought about in my head. I was sold. I knew what I
wanted to do in my life. Computers understood me and I knew how to talk to them.

## Mode 13h

```asm
mov ax, 13h ; AH=0 (Change video mode), AL=13h (Mode)
int 10h     ; Video BIOS interrupt
```

Jumping forward a few years. I had killed and reinstalled the family computer
at least twice or three times, attempting to install old Linux distros found on
computer magazines CD-ROMs. And then I discovered the demo scene.

Developing applications in C was fun but going even deeper into understanding
the hardware and how to interact with it, optimize code and, in doing so, being
able to display crazy graphics in only a few kilobytes was my new Everest.

## Back to the real world

```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
```

I was a decent student, working just enough to reach my goals. I secured a spot
in a telecommunications engineering school. I focused my curriculum on IT and
programming. The language of choice there was Java. They fed us so many ugly
skeletons for coding exercises that I grew totally frustrated with object-oriented
programming, to the point where I could not bear it anymore. This was not what code
meant to me ; I needed something rawer, closer to the machine.

During my student years I had the opportunity to work one year as an embedded
software developer intern in a big silicon company. The experience was
eye-opening. It combined low-level programming, bare-metal optimizations,
driver development, all the things that had put stars in my eyes in the first
place.

## Hello work

```c
uintptr_t res;

if (__builtin_add_overflow(address, size, &res)) {
    // Overflow
} else {
    // No overflow
}
```

After school, my first job as a software developer was in a small French
company working on secure operating systems. I learned that as powerful a
language it can be, C can also be tricky and one can easily shoot oneself in
the foot if not careful enough. Understanding the language itself and the tools
around it is equally as important as writing software itself.

All the past experiences I had converged into a deep expertise of how hardware
worked, how software ran on a given architecture, what are the concepts behind
a language, its compilers, etc. I discovered what a stack or a heap overflow
is, and other even nastier stuff, and more importantly how to try and prevent
them.

## Hello, new world!

```rust
fn main() {
    println!("Hello, new world!");
}
```

What's to come now? I don't develop much now that I have higher management
responsibilities. Do I miss writing code? Maybe a little. Do I want to go back
to development? Probably not. I guess the way forward is for me to keep an eye
on new technologies and use some personal time to not get too rusty (pun
intended).
