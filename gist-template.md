# Title (replace with your title)

This tutorial explains how to match a URL using a regular expression by breaking down each part of the expression and explaining what it does. The regular expression pattern is ^(https?://)?([a-z0-9-]+\.)+[a-z]{2,}(:\d{1,5})?(/.*)?$ and it matches a URL that starts with an optional http or https protocol, followed by one or more subdomains (each containing letters, digits, and hyphens) separated by dots, a top-level domain with two or more letters, an optional port number (preceded by a colon and containing between 1 and 5 digits), and an optional path (which can contain any combination of characters)

## Summary

The readme file provides a comprehensive guide on how to match a URL using a regular expression. It describes each part of the regular expression pattern ^(https?://)?([a-z0-9-]+\.)+[a-z]{2,}(:\d{1,5})?(/.*)?$ and explains what it does. It also provides examples of strings that would match and strings that would not match the pattern. This tutorial is useful for anyone who wants to learn how to use regular expressions for pattern matching, particularly in the context of URLs.

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
^(https?://)?([a-z0-9-]+\.)+[a-z]{2,}(:\d{1,5})?(/.*)?$

(https?://)? - This part matches the protocol of the URL, which can be either http or https, followed by ://. The ? means that this part of the pattern is optional, so URLs without a protocol will still match

### Anchors
`^` - This symbol signifies the beginning of the string
`$` - This symbol signifies the end of the string.

### Quantifiers
`?` - This symbol signifies that the preceding character or group is optional and may appear once or not at all.
`+` - This symbol signifies that the preceding character or group must appear one or more times.
{n,m} - This symbol signifies that the preceding character or group must appear at least n times and at most m times.
`*` - This symbol signifies that the preceding character or group can appear zero or more times

### Grouping Constructs
`()` - This symbol groups characters or expressions together and creates a capture group.
`(?:)` - This symbol groups characters or expressions together but does not create a capture group

### Bracket Expressions
`[]` - This symbol matches any character inside the brackets.
`[^]` - This symbol matches any character that is not inside the brackets

### Character Classes
`\d `- This symbol matches any digit character.
`\w` - This symbol matches any word character (letters, digits, or underscores).
`\s` - This symbol matches any whitespace character.
`.` - This symbol matches any character except a newline character

### The OR Operator
 `|` - This symbol matches either the expression on the left or the expression on the right
### Flags
`i` - This flag signifies that the regular expression is case-insensitive.
`g` - This flag signifies that the regular expression should match all occurrences in the input string

### Character Escapes
`\` - This symbol is used to escape special characters so that they are treated as literal characters.
The regular expression pattern `(https?://)?([a-z0-9-]+\.)+[a-z]{2,}(:\d{1,5})?(/.*)?$` contains several of these elements, including anchors, quantifiers, grouping constructs, bracket expressions, character classes, the OR operator, flags, and character escapes. This pattern matches a URL that starts with an optional `http` or `https `protocol, followed by one or more subdomains (each containing letters, digits, and hyphens) separated by dots, a top-level domain with two or more letters, an optional port number (preceded by a colon and containing between 1 and 5 digits), and an optional path (which can contain any combination of characters).

## Author

https://github.com/Abela24
