# Regex Tutorial: A Hands-On Introduction to Regular Expressions

## Introduction

In this tutorial, we'll explore the fundamentals of regular expressions, commonly referred to as regex. Regular expressions are powerful tools for pattern matching and text manipulation. Whether you're a beginner or an experienced developer, understanding regex can greatly enhance your ability to work with textual data.

## Summary

We'll focus on a specific regex pattern for matching email addresses. This pattern will cover the essential components of an email address and provide insights into building robust regex expressions.

Regex Pattern:
^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$

Throughout the tutorial, we'll explain each component of this regex pattern in detail, covering its purpose and how it contributes to validating email addresses.

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
Anchors (^, $, \b, and \B) are essential for specifying where in the text a match should occur.

### Quantifiers
Quantifiers (*, +, ?, {}) allow us to specify how many times a character or a group of characters can appear in a match. 

### OR Operator
In regular expressions, the '|' symbol is used to denote the "or" operator, allowing you to match either one pattern or another. It's often referred to as alternation.

For example, suppose we want to match either "cat" or "dog" in a text. We can use the regex pattern cat|dog. Here's what each part of the pattern does:

- cat: Matches the exact string "cat".
- |: Acts as the "or" operator.
- dog: Matches the exact string "dog".

### Character Classes
Character classes provide a way to match any one of a set of characters. You can learn how to use [ ] to create character classes and negate them using ^.

### Flags
In regular expressions, flags are modifiers that can be added to the end of a regex pattern to change how the pattern is interpreted or applied. They alter the behavior of the regex engine when matching text.

### Grouping and Capturing
Grouping allows us to treat multiple characters as a single unit. You can learn how to explore the use of () for grouping and capturing substrings.

### Bracket Expressions
In regular expressions, bracket expressions, also known as character classes, allow you to specify a set of characters that you want to match. They are enclosed within square brackets [ ]. For example, [aeiou] matches any single vowel character (a, e, i, o, or u). 

### Greedy and Lazy Match
In regular expressions, quantifiers such as *, +, and {} are greedy by default, meaning they match as much text as possible while still allowing the overall pattern to match. However, sometimes you may want to match as little text as possible. This is where lazy (or non-greedy) matching comes into play. Lazy quantifiers, denoted by appending a ? after the quantifier, match as little text as possible while still allowing the overall pattern to match.

### Boundaries
In regular expressions, boundaries help define where a match should start or end within the text. They do not match any characters themselves but rather represent positions within the text.

### Back-references
In regular expressions, back references allow you to match the same text that was previously matched by a capturing group. They enable you to refer back to portions of the input text that have already been matched. To create a back reference, you use a backslash \ followed by the index or name of the capturing group you want to reference. 

### Look-ahead and Look-behind
In regular expressions, look-ahead and look-behind assertions are zero-width assertions, meaning they don't consume characters in the input string but only assert whether a match is possible at a specific position. A look-ahead assertion, denoted by (?= ...), asserts whether a particular pattern matches next in the input text without consuming any characters. It's used to check if a certain pattern is followed by another pattern.

## Author

This tutorial was writen by Vineysha. You can find more of my work at my GitHub [https://github.com/Vineysha]