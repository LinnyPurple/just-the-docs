---
layout: default
title: Reference Guide
nav_order: 3
---

# Reference Guide
{: .no_toc }

On this page, you'll find some helpful reminders and tips about this programming language.

## Website
The website we will use to run sample Brainfuck codes is [https://copy.sh/brainfuck/](https://copy.sh/brainfuck/)

## Symbols

`>` Move one cell to the right.

`<` Move one cell to the left.

`+` Increment the current cell by one.

`-` Decrement the current cell by one.

`.` Output the current cell's value to the console.

`,` Get the next character in the input and store it in the current cell.

`[` Signal the start of a loop.

`]` Signal the end of a loop.

## Simple Functions

`[-]` Set the value of the current cell to 0.

`[-<+>]` Add the current cell to the cell on the left. Current cell's value will become 0 in the process.

`[-<->]` Subtract the current cell from the cell on the left. Current cell's value will become 0 in the process.

## ASCII Table

Given the table below, the ASCII value of that number will be the output to the console rather than the number itself. For example, if the value of the current cell is `48`, the console's output is `0`.

![ASKEE TABLE](https://github.com/LinnyPurple/Lachlan-George-Joey/blob/gh-pages/assets/images/ASKEE%20table.png?raw=true "ASCII Tabe")

## Cell Table

In this language, there are 30,000 "cells" which store a value. Each cell can hold any number between 0 and 255. The pointer is always pointing to one of these cells. Whichever cell the pointer is pointing at will be the one affected by an instruction.

![Memory dump](https://github.com/LinnyPurple/Lachlan-George-Joey/blob/gh-pages/assets/images/Memory%20dump.png?raw=true "memorydump")
