# URL Regex

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

The regex that is being covered is a url regular expression or in a simplified manner true to its functionality and creation is the regex.
Example of URL regex:
`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Back-references](#back-references)
- [Author](#author)

## Regex Components

URL Regex
`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

### Anchors

The anchors within this regex are the ^ and the $ which are located respectively at the initiation of the regex and the ending of the regex. Anchors are explicit in defining the start of the regex pattern that will be used as parameters all through the $.

### Quantifiers

One of the considered quatifiers that is presented in this example are commonly known by the {} curly brackets. Commonly known to be greedy. These curly bracket quatifiers are a set of 3 different quantifierise limiting the possible matches.In this case {2,6} a minimum of 2 and a maximum of 6 characters in any combination manner considering the preceding pattern of [a-z\.] .

### Character Classes
The character classes are a section of groups representing variaties of characters all of which might be present in an expression for matching purposes.
the character class of \d is a represntation of numbers ranging from [0-9]. The \w is a alphanumeric character based off of latin alphabet including the underscore this class is equivalent to the pattern [A-Za-z0-9_].   These are compacted and  are commonly used for efficiency purposes.
\d \w  {}

### Grouping and Capturing
due to the nature in complexity of a regex in how it intrecate it grows to be when determining the patterns that are being checked the use of grouping the patterns is helpful and useful. these sections are broken up within two parenthesis () breaking up the sections for the regex.
grouping constructs ()

### Bracket Expressions

[\da-z\.-] [a-z\.] [\/\w \.-]
 The [] square brackets determine the range of characters and patterns that are required for the expression. 

### Greedy and Lazy Match

{}

- ? +

### Back-references

\ no special meaning behind these backslashes. It allows for characters to be used within the regex quite literally.

## Author
Passionate to learn about the tech world.
My GitHub:
https://github.com/EvelynMS1
