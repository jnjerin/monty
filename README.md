# monty

## The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

## Introduction
Our program parses and interprets files of Monty bytecode, allowing the user to store integer values to a stack and to perform manipulations on both the stack and contained values. 

## Installation
To install our interpreter on your Linux machine, clone the contents of this repository into a new directory and compile with the command:

    gcc *.c -o monty
