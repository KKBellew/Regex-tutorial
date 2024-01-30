# Regex-tutorial
In this tutorial it will explain how a specific expression, or regex, functions by breaking down each part of the expression and describing what it does, SO THAT you can understand the search pattern that the regex defines.

## Summary

The featured regex in this tutorial is designed to match specific patterns within text. Regex is an encoded text string that computer programmers use as search patterns for matching sets of strings. These expressions provide a concise and flexible way of matching various text strings. As we dive into its components, you'll begin to understand how it all functions.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

These characters give details about the location within a particular string a user is trying to search. It helps in searching within lines. Usually, for finding character A in a string, you can use the following characters to find a match within a line:

A$: Helps in matching at the end of a line.
^A: Helps in matching at the beginning of a line.

### Quantifiers

Quantifiers help in defining quantities for a search string. Some commonly used quantifiers are:

n+: Matches any string containing at least one n.
n?: Matches any string containing zero or one occurrence of n.
n*: Matches any string containing zero or more occurrences of n.

### Grouping Constructs



(?:grouping)

### Bracket Expressions

Square Brackets- shows one character of the regex.
[a-zA-Z]
Parenetheses- Creates a sequence or sub-expression.
(a-za-Z)

### Character Classes
Help you define parameters for the type of text you want to search. For instance, you can use [0-9] to search for numerical ranges. Interestingly, regex allows programmers to find letter ranges or support alternate spellings. For example, so[ml]e matches both some and sole. Some commonly used character sets are:

[a-z]: Helps in matching lowercase letters from a to z.
[A-Z]: Helps in matching uppercase letters from A to Z.
[0-9]: Helps match a range of numbers from 0 to 9.
[.]: Helps match any character, except line break characters.


### The OR Operator

Is signified by the `|` character. The OR Operator is used when the user wants to inform the regex that not every search parameter must be met. Rather, it can be one or several search parameters being met to yield a result. 

pattern1|pattern2

### Flags



/pattern/gi

### Character Escapes



\$

## Author

This tutorial is made by Kayleena Bellew, I am currently a student in full stack web-dev at KU, a regex beginner but did a lot of research to get the most informational tutorial. Check out my profile at (https://github.com/KKBellew/ ).

extras- sites where i obtiained the info for this tutorial from. 
1.https://www.variables.sh/what-is-regex/
2.indeed.com
3.mozilla
