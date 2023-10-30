#Palindrome Checker Algorithm

Description:
This algorithm checks if a given word is a palindrome. A word is considered a palindrome if it reads the same from left to right as well as from right to left.

Algorithm:
Define two pointers, i and j, initialized to the start and end of the word respectively.

Use a WHILE loop to iterate as long as i is less than j.
Within the loop, compare characters at positions i and j.

If they are not equal, return FALSE as it's not a palindrome.
Otherwise, move i one position to the right and j one position to the left.

If the loop completes without finding any differences, return TRUE as it's a palindrome.

Stop Condition:
If the word is empty or contains a single character, it is considered a palindrome.

Usage:
Call the function isPalindrome(word) with the word you want to check for palindromes.

Example:

    isPalindrome("radar") => TRUE
    isPalindrome("hello") => FALSE
