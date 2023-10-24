# IP Address

For this homework assignment I will be demoing the IP Address regex expression.

## Summary
This regex expression is designed to match and validate IPv4 addresses within a text string.

IP Address Expression `^((?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?))*$`

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
* Numeric Ranges.
* Dot Seperators
* Capture groups.


### Anchors
The Anchors used in this regex expression are 
* `^`. When ^ is placed at the beginning of a regex pattern, it ensures that the match occurs at the very start of the input.

* `$`. When $ is placed at the end of a regex pattern, it ensures that the match occurs at the very end of the input. 

### Quantifiers
Quantifiers used in this regex expression are
*`*` Asterisk is a quantifier that specifies that the preceding element should be matched zero or more times.

* `{}` Curly brackets are used to specify the exact number of times a preceding element should be matched. It allows you to set a specific range or a fixed count for the element's repetitions.

* `?` Question mark is often used when you want to indicate that a particular element or part of a pattern is optional, and it may or may not appear in the input string. It allows you to match patterns with or without the optional element.


### Grouping Constructs
Grouping constructs used in this regex expression are
* Capture Groups `()`. Parentheses serve multiple purposes in regex patterns, such as creating capturing groups, grouping for quantification, organizing subpatterns, and defining alternations. They are essential for controlling the behavior and structure of 
the pattern and capturing specific parts of the matched text.

* Non-Capturing Groups `(?:.)`. Non-capturing groups are particularly useful when you want to structure and optimize your regex pattern without the need to capture specific subpatterns. They help ensure that the capture groups focus on the information you want to extract from the input string.



### Bracket Expressions
* There are no brackets expressions used in this expression.


### Character Classes
* There are no character classes used in this expression.


### The OR Operator
* The OR Operator used in this expression is represented by `|`.
The alternation operator | is a tool for expressing choices in your regex pattern. It allows you to search for any one of several possible options within the input text.


### Flags
 Flags in regex are typically used after the regex pattern itself and modify how the pattern is applied.

### Character Escapes
* `\` The backslash is used in this expression. The backslash \ in a regex pattern is used to modify the interpretation of the character that follows it, treating it as a literal character rather than a special metacharacter. It is a fundamental component for specifying precise text matching in regular expressions.

## Author

The author for this expression is Jackson F. de A. Mafra.
Jackson is a Brazilian software engineer living in Stockholm 🇸🇪.

* https://gist.github.com/jacksonfdam

