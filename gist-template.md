# Regex Tutorial ()
Welcome to this tutorial on regular expressions of regex, the powerful tool for pattern matching and text manipulation.
Whether you are a beginner or a experienced developer, understanding regex can enhance your coding skills.
In this tutorial we will break down the various components of regex and how the work to create search patterns.


## Summary
In this tutorial we will dive into a comprehensive explanation of a regular expression and its components.
The regex we will be exploring is 
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`(email address)
We will look at different elements of the regex like,
Anchors, Quantifiers, Grouping Constructs, Bracket Expressions, Character Classes,
The OR operator, Flags,and Character Escapes.


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
At the beginning of the regex we have the '^' symbol and at the end. We also have the $ symbol.
These symbols are called anchors =. They indicate the start and the end of the line.In our regex
they ensure that the email address is matched from start to finish with no extra characters before or after the email.

### Quantifiers
Quantifiers allow us to specify how many times a character should appear in the input. 
We will explore quantifiers like '+', '*', '?',and '{}', and how the affect the matching process.

### Grouping Constructs
Grouping constructs '( )' allow us to create a sub expressions within our regex. This ables us to 
apply quantifiers or other operations to multiple characters as a single unit.

### Bracket Expressions
Bracket expressions '[ ]' define the character set, allowing us to match any one character from one set.


### Character Classes
character classes like '\w', '\d', and '\s' represent shorthand for common sets of characters.

### The OR Operator
The '|' symbol, known as the OR operator allows us to create alternative matching options within our regex.

### Flags
Flags like 'i', and 'g',and 'm' can modify the behavior of our regex

### Character Escapes
Character escapes, denoted by '\', allow us to match special characters as literal characters.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
