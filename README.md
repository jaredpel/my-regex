# Regex Tutorial Starter Code

Introductory paragraph (replace this with your text)

## Summary

in this tutorial it will explain how it works with emails

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)

## Regex Components

### Anchors

The anchors that use regular expression are, ^ which is used to start it and to end it itll need a $.

### Quantifiers

when we use + to communicate as a quantifier, there is also another use of quantifiers such as {2,6}, this tells it it should be a minimum and a maximum of characters.

### OR Operator

The OR operator (|) means the expression [123] can be written (1|2|3)

### Character Classes

the character class \w is used for regex and its classified as any word.

### Grouping and Capturing

there are three groups, first one is /^w+[+.w-]*@ username, second one is
([w-]+.)*w+[w-]* the domain name, the third one is ([a-z]{2,4}|d+)$/i the extension.

### Bracket Expressions

there are 4 different bracket expressions and it is put together with [].

### Greedy and Lazy Match

greedy quantifiers + and {}, mean that it will allow the match to expand, if the quantifiers are lazy they would be +? and {}?.

### Boundaries

boundriesd are when you want to match a sequence of letters on their own, or they occur at the beginning or the end of a sequence of characters.

### Back-references

Back-references are used to match the same text previously matched by a capturing group.

## Author

https://github.com/jaredpel/my-regex 