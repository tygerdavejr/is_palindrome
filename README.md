# is_palindrome
Module 8 Lab: Determine if a word is a palindrome

David Vance
Professor Kevin Chang
CIS129 - Programming and Problem Solving
16 October 2024

Module 8 Lab:
    Write the function is_palindrome that takes a string and returns True if it's a palindrome and False otherwise.  Use a stack (simulated with a list as in Section 5.11) to help determine whether a string is a palindrome.  Your function should ignore case sensitivity, spaces and punctuation.

Pseudocode
    Input a word
    Strip non-letters from the word
    convert the word to all upper case
    assign the word to a list; 'PALINDROME' becomes ['P', 'A', 'L', 'I', 'N', 'D', 'R', 'O', 'M', 'E']
    Loop from 1 to length of word
        Push each letter to the stack
    Assign the return value to True
    While return value == True
        Loop from 1 to length of the word
            Pull a letter from the stack, and compare to the appropriate letter in the word list
            if the letter from the stack does not equal the letter from the word
                Assign the return value to False
    Return value
        
