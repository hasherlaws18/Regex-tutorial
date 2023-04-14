Regex Explained. 

In this Read me I will explain what Regex is and what the Regex compents are.

## Summary

The short definition for Regex is that it is a sequence of chararacters that Defines a specific search pattern. So what it basically does is that it accpets a certain set of strings and then rejects the rest of them. I will show all the componetnts of a regex below.

Here is a exapmle of Regex matching an email.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

Anchors belong to the family of regex tokens that do not match any characters, but they instert something in the string. Anchors assert engine current postitin in the string matches a well-determined location.
 
 Heres an exapmle of Anchors 
 /^hello/

### Quantifiers
 
 In regular expressions quantifiers are components that allow you to specifiy how many times a paticular patter should appear in the text you are searching or matching.

 Heres an example of Quantifiers
 \d{3,}

### OR Operator

The OR operator allows you to create a refular expression that will match multiple patterns rather han just a single pattern.

Heres an example of  a OR Operator

Red|Blue

### Character Classes

Character class are also called character set. You can put characters you want to match between square brackets.

Heres an example of Character classes
[0-9]

### Flags
Flags are typically specified as a single letter after the closing delimiter of the regular expression.

Here is an example of Flags
`/hello/gi`
### Grouping and Capturing


### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
