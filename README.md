# ECE2112_PA1
## EXPERIMENT 1: INTRODUCTION TO PYTHON PROGRAMMING
Florence Miguel S. Araga | 2ECE-A

### OBJECTIVES:
At the end of this laboratory activity, the student should be able to:
1. use basic Python functions, operators, and string operations;
2. manipulate strings using indexing, slicing, and built-in string methods;
3. apply sequence unpacking to manipulate the elements of a list; and
4. construct simple Python functions that return a specified result.

### A. WORD ROTATION PROBLEM
Create a function named rotate word() that accepts a non-empty string. Move the first character
of the string to the end while keeping all remaining characters in their original order. Preserve the
capitalization of every character.
Requirement: Use string indexing or slicing to construct the returned string.

### B. USERNAME BUILDER PROBLEM
Create a function named make username() that accepts two strings: first name and last name. The
function must:
1. convert all letters to lowercase;
2. remove all spaces from the first name;
3. remove all spaces from the last name; and
4. join the processed first and last names using one period (.)
Requirement: Use basic string methods and string concatenation. Return the completed username.

### C. BOOKEND SWAP PROBLEM
Create a function named swap bookends() that accepts a list containing at least two elements. Unpack
the list into three variables:
• first – the first element;
• middle – a list containing everything between the first and last elements; and
• last – the last element.
Using these variables, return a new list in which the first and last elements have exchanged positions.
The elements in middle must remain in their original order. Do not modify the input list.
Requirement: Use extended sequence unpacking in the following form:
first, *middle, last = items
