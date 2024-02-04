# Regex Tutorial 

Regex is called a regular expression. Is is composed of a sequence of characters that allows matching and location of designated text patterns. 
It allows you to define a search pattern, which can be used to match, find, or replace strings in a text.

## Summary

Will be explaing the use of the hex key value regex `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
 Anchors are metacharacters used to assert a position within the input string.
`^` and `$`are common used anchors. 
Entire string matches the pattern

### Quantifiers
They are symbols or metacharacters that specify the number of occurrences of a character or a group of characters. They allow you to define the quantity or repetition of the preceding element in the regex pattern. They can be presenet or absent.
Examples: `?` and `{n}`
There are 6 quantifiers matching charcters. 
Example: `{6}` is a quantifier that specifies the exact repetition count. This a quantifier that specifies the exact repetition count. 


### OR Operator
Allows you to create a pattern that matches either the expression on its left side or the expression on its right side. It functions similarly to a logical OR, where one of the conditions needs to be true for a match.
Example: `|` 


### Character Classes
A way to represent a group of characters that you want to match at a particular position in a string. Allow matching of a character within a set. 
Example: `a-f0-9` 


### Grouping and Capturing
Parentheses are used to group parts of a regex into a single unit. This can be helpful for applying quantifiers or other operations to a specific part of the pattern.Allows caputing anything within the construtors. 
`()`

### Bracket Expressions
They allow you to define a range or a list of characters from which a single character should match.
Example: `[]`
This case: [a-f0-9] matches a single character that is a hexadecimal digit.

### Look-ahead and Look-behind
Look-ahead and look-behind are zero-width assertions in regular expressions that allow you to check for the presence or absence of a certain pattern without including it in the match itself. They are used to impose conditions on the characters that precede or follow a specific position in the input string.

## Author
[Eli Soto](https://github.com/eli-soto)