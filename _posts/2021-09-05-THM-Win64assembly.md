---
title:  Windows x64 Assembly
name: CYB3RM3 | Windows x64 Assembly
date:   2021-09-05 18:35:57
categories: [CTF]
tags: [TryHackMe, assembly]
---

Introduction to x64 Assembly on Windows.

THM Room [https://tryhackme.com/room/win64assembly](https://tryhackme.com/room/win64assembly)  

# Table of contents
1. [TASK 1 : Introduction](#Introduction)
2. [TASK 2 : Number Systems](#NumberSystems)
3. [Task 3 : Bits and Bytes](#BitsandBytes)
4. [TASK 4 : Binary Operations](#BinaryOperations)
5. [TASK 5 : Registers](#Registers)
6. [TASK 6 : Instructions](#Instructions)
7. [TASK 7 : Flags](#Flags)
8. [TASK 8 : Calling Conventions](#CallingConventions)
9. [TASK 9 : Memory Layout](#MemoryLayout)
10. [TASK 10 : Final Thoughts ](#FinalThoughts)

## **TASK 1 : Introduction** <a name="Introduction"></a>
No answer needed

## **TASK 2 : Number Systems** <a name="NumberSystems"></a>

* ####  What is 0xA in decimal?

Answer : 10

* #### What is decimal 25 in hexadecimal? Include the prefix for hexadecimal.
Answer : 0x19

## **TASK 3 : Bits and Bytes** <a name="BitsandBytes"></a>

* #### How many bytes is a WORD ?
Answer : 2

* #### How many bits is a WORD ?
Answer : 16

## **TASK 4 : Binary Operations** <a name="BinaryOperations"></a>

* #### What is the result of the binary operation: 1011 AND 1100 ?
Answer : 1000

* #### What is the result of the binary operation: 1011 NAND 1100? Include leading zeroes.
Answer : 0111

## **TASK 5 : Registers** <a name="Registers"></a>

* #### How many bytes is RAX ?
Answer : 8

* #### How many bytes is EAX ?
Answer : 4

## **TASK 6 : Instructions** <a name="Instructions"></a>

* #### What instruction returns from a function ?
Answer : ret

* #### What instruction will call/execute a function ?
Answer : call

* #### What instruction could be used to save a register in a way that it can later be restored ?
Answer : push

## **TASK 7 : Flags** <a name="Flags"></a>

* #### If two equal values are compared to each other, what will ZF be set to as result of the comparison ?
Answer : 1

## **TASK 8 : Calling Conventions** <a name="CallingConventions"></a>

* #### In fastcall, what 64-bit register will hold the return value of a function ?
Answer : RAX  

* #### In fastcall, what register is the first function parameter passed in ?
Answer : RCX  

## **TASK 9 : Memory Layout** <a name="MemoryLayout"></a>

* #### In what order is data taken off of or put onto the stack? Provide the acronym.  

Answer : LIFO (Last In First Out)  

## **TASK 10 : Final thoughts** <a name="Finalthoughts"></a>

Go forth and do great things !  
No Answer