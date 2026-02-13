# Phase 6 – Code Generation

## Description
Converts intermediate code into target machine instructions.

## Instructions Used
MOV
ADD
MUL

## Input File
input.txt

## Sample Input
t1 = c * d
t2 = b + t1

## Sample Output
MOV R1, c
MUL R1, d
MOV t1, R1
MOV R2, b
ADD R2, t1
MOV t2, R2

## Run
python codegen.py
