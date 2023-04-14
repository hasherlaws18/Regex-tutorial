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

In regular expressions, grouping and capturing are used to extract specific parts of a matched string. Grouping is the process of enclosing a portion of the regular expression pattern in parentheses (()), which creates a group. Capturing is the process of storing the matched substring of a group in a separate memory location, which can be accessed later.

Here is example of Grouping and Capturing
(\w+)\s+(\w+)\s+\((\d+)\)


### Bracket Expressions
 A bracket expression is a way to match a single character from a set of range of characters.

 Here is example of Bracket Expressions

 [abc]

### Greedy and Lazy Match
Greedy and lazy matching refer to how the regex engine tries to match patterns.

Here is example of Greedy and Lazy Match

'a+' == 'aaa'

### Boundaries
In regular expressions, boundaries are used to match positions within the input string instead of matching characters. Boundaries can be used to match the beginning or end of a word, the beginning or end of a line, or the boundary between a word character and a non-word character.

Here is example of Boundaries
/bdog

### Back-references
back-references are regular expression commands which refer to a previous part of the matched regular expression. 

Here is example of back-references
(\w+)\s\1
### Look-ahead and Look-behind

Lookahead and lookbehind are advanced features in regular expressions that allow you to check for a pattern ahead of or behind the current matching position, without actually including it in the match. 

Here is example of Look-ahead and Look-behind
 hello(?= world): 

## Author

Houston Asher-Laws https://github.com/hasherlaws18
