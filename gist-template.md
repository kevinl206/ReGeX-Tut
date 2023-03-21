# Regex Tutorial

This tutorial will help developer understand how Regex, short for Regular Expression, is a sequence of characters that form a pattern that can be used to match and manipulate text.

## Summary

The way regex works is by defining a pattern that describes the desired text to be matched or manipulated. This pattern can include various symbols and special characters that have specific meanings.

For example, the symbol "." in a regex pattern matches any single character, while the symbol "*" matches zero or more occurrences of the previous character.

When a regex pattern is applied to a text, it searches for matches of the pattern within the text. If a match is found, the regex engine can perform various operations on the matched text, such as replacing it with new text or extracting certain parts of it.

Regex is commonly used in programming languages, text editors, and other software tools for tasks such as data validation, text search and replace, and parsing text into structured data.

The tutorial will walk you through a code to looks a matching emails.

Example: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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
An anchor is a zero-width assertion that specifies a position in the text where the match should start or end. In the example code /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/, the(^) and ($) are anchors that specify the start and end of the text to be matched, respectively.

* The (^) specifies that the match should start at the beginning of the text.
* The ($) specifies that the match should end at the end of the text.

### Quantifiers
* *: Matches the preceding element zero or more times. For example, the pattern a* would match zero or more occurrences of the letter "a". In this case, the first capturing group ([a-z0-9_\.-]+) matches one or more occurrences of lowercase letters (a-z), numbers (0-9), underscores (_), dots (.), and hyphens (-) in the local part of the email address. This ensures that the local part is not empty.


* +: Matches the preceding element one or more times. For example, the pattern a+ would match one or more occurrences of the letter "a".

* ?: Matches the preceding element zero or one time.

* +: Matches the pattern one or more time.

Quantifiers can be used with characters, character classes, groups, and even with other quantifiers.

### OR Operator
The OR operator (|) is used to specify a disjunction. For example, the pattern a|b|c matches either the letter "a", the letter "b", or the letter "c". 

### Character Classes


### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
