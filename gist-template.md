# URL Regex

Regex patterns are used for a wide range of identifying text patterns in a simplified understandable manner that has versitile functionalities ranging to be used for personal files to algorithims for the purpose of input validation, find and replace and many more purposes.

## Summary

The regex that is being covered is a url regular expression or in a simplified manner true to its functionality and creation is the regex. I will explain each section of this regex pattern. <br/>
Example of URL regex:<br/>
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

The anchors within this regex are the `^` and the `$` which are located respectively at the initiation of the regex and the ending of the regex. Anchors are explicit in defining the start of the regex pattern that will be used as parameters all through the `$`.

### Quantifiers

`([a-z\.]{2,6})` <br/>
One of the considered quatifiers that is presented in this example are commonly known by the `{}` curly brackets. Commonly known to be greedy. These curly bracket quatifiers is one of the 3 different quantifiers that limits the possible matches. In this case `{2,6}`, representing that a minimum of 2 and a maximum of 6 characters in any combination manner must be present of the preceding pattern of `[a-z\.]`.An example that would qualify for this quantifier would be bw or jfsc. The reason why the first one meets the expectation is because it is a minimum of 2 characters ranging from a through z lowercase.The second example passes as well it falls between a minimum 2 and maximum of 6 characters, in this case a total of 5 and all lowercase a-z with one period. It doesnt have to include all of the requirement meaning that it doesnt need a period as long as it meets the requirement of 2 to 6 characters.

### Character Classes

Examples: `\d \w {}` <br/>
The character classes are special characters representing varieties of characters all of which might be present in an expression for matching purposes.
The character class of \d is a representation of numbers ranging from `[0-9]`. The `\w` is a alphanumeric character based off of the latin alphabet which includes the underscore, this class is equivalent to the pattern `[A-Za-z0-9_]`. These are compacted and are commonly used for efficiency purposes.

### Grouping and Capturing

In our regex example the `(https?:\/\/)` <br/>
Due to the nature in complexity of a regex in how intrecate it grows. For the purpose of determining the patterns that are being checked the curciality of grouping the patterns is helpful and useful. These sections are broken up within two parenthesis `()` breaking up the sections for the regex also known as grouping constructs.

### Bracket Expressions

`[\da-z\.-] [a-z\.] [\/\w \.-]` <br/>
The `[]` square brackets determine the range of characters and patterns that are required for the expression. In this example, `[\da-z\.-]`, this bracket expression is looking for `\d` a number between `0-9`, lowercase `a-z`, a period and a `-`. Therefore any representation of this pattern would do. An example of this would be anything that meets one of these requirement
ex: kaMI. this would meet the regex pattern because it has a lowercase letter a and it has a period as well.

### Greedy and Lazy Match

Examples: `{} ? +` <br/>
`(https?:\/\/)?`<br/>
The lazy match in this case is the `?` that comes after the https meaning that it tries to match as little as possible, in this case zero or one time, it is optional.The `?` after the group signifies that it is optional to add the precedding group.<br/>
`([\da-z\.-]+)`<br/>
The `+` greedy match, matches the preceding character more than one time. In other words it tries to find the pattern more then once.

### Back-references

`[a-z\.]` <br/>
This means no special meaning behind these backslashes. It allows for characters to be used within the regex quite literally. An example would be `\.`. In our regex pattern a the period it is looking for is a singular period.

## Author

Passionate to learn about the tech world.
My GitHub: https://github.com/EvelynMS1
