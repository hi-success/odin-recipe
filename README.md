# File Name Search Program in C

## Description
This project is a simple C program that allows the user to enter three file names and a search word.

The program checks whether the search word appears inside any of the entered file names and displays the result.

## Features
- Accepts three file names from the user
- Accepts a search word
- Checks if the search word exists inside each file name
- Displays whether a match was found or not

## Technologies Used
- C Programming Language
- Standard C Libraries (`stdio.h`, `string.h`)

## How It Works
1. The user enters three file names
2. The user enters a search word
3. The program checks each file name using string search
4. It displays whether a match exists in each file name

## Example Use Case
If the user enters:

File names:
- assignment.txt
- report.doc
- project_notes.pdf

Search word:
- port

Output:
- assignment.txt -> No match found.
- report.doc -> Match found!
- project_notes.pdf -> No match found.

## What I Learned
This project helped me practice:
- strings in C
- user input
- the `strstr()` function
- conditional statements
- problem solving

## Future Improvements
- Allow more than three file names
- Make the search case-insensitive
- Search inside actual file contents
- Store file names in an array for better structure
