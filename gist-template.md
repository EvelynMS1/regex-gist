# URL Regex

Regex patterns are used for a wide range of identifying text patterns in a simplified understandable manner that has versitile functionalities ranging to be used for personal files to algorithims for the purpose of input validation, find and replace and many more purposes.

## Summary

The regex that is being covered is a url regular expression or in a simplified manner true to its functionality and creation is the regex. I will explain each section of this regex pattern.
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

One of the considered quatifiers that is presented in this example are commonly known by the {} curly brackets. Commonly known to be greedy. These curly bracket quatifiers are a set of 3 different quantifierise limiting the possible matches.In this case {2,6} a minimum of 2 and a maximum of 6 characters in any combination manner considering the preceding pattern of [a-z\.]. An example that would qualify for this quantifier would be bw or jfsc. the first on is a minimum of 2 characters ranging from A through Z and can include a . it doesnt have to include all of the requirement meaning that it doesnt need a period as long as it meets the requirement of 2 to 6 characters.

### Character Classes

The character classes are a section of groups representing variaties of characters all of which might be present in an expression for matching purposes.
the character class of \d is a represntation of numbers ranging from [0-9]. The \w is a alphanumeric character based off of latin alphabet including the underscore this class is equivalent to the pattern [A-Za-z0-9_]. These are compacted and are commonly used for efficiency purposes.
\d \w {}

### Grouping and Capturing

due to the nature in complexity of a regex in how it intrecate it grows to be when determining the patterns that are being checked the use of grouping the patterns is helpful and useful. these sections are broken up within two parenthesis () breaking up the sections for the regex.
grouping constructs ()
In our regex example the `(https?:\/\/)`

### Bracket Expressions

[\da-z\.-] [a-z\.] [\/\w \.-]
The [] square brackets determine the range of characters and patterns that are required for the expression. In this example [\da-z\.-] this bracket expression is looking for \d number 0-9, lowercase a-z a period and a - therefore any representation of this pattern would do. An example of this would be anything that meets one of these requirement
ex: kaMI. this would meet the regex pattern because it has a lowercase letter a and it has a period as well.

### Greedy and Lazy Match

{} ? +
the lazy match in this case is the ? that comes after the https? meaning that it tries to match as little as possible, in this case zero or one time.

the + greedy match matches the precedding character more than one time .

### Back-references

\ no special meaning behind these backslashes. It allows for characters to be used within the regex quite literally. An example would be `\.` in our rege pattern a [a-z\.] in this case the period it is looking for a singular period.

## Author

Passionate to learn about the tech world.
My GitHub:
https://github.com/EvelynMS1
