# Regex Email Tutorial!

⚡ Tutorial on how to use Regex to verify Emails!
(Note to self) Reuploaded to Github because I won't remember the gist.github link...
https://gist.github.com/singharaj-usai/109a4241bb48965f6e0bf82a1895b190

## Summary

💻 Regex examples and descriptions for emails. Because we didn't learn that much about Regex in class, I had to use a YouTube video to learn what Regex is: https://www.youtube.com/watch?v=909NfO1St0A

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

```md
let RegexEmail = /^w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/;
```
Everything after let "RegexEmail =" creates the Regular Expressions (AKA Regex).

The ^ caret is the beginning of the line, the $ dollar sign is the end of it. ``` /^w+([\.-]?\w+)*@``` That part is where it begins.

### Quantifiers

Quantifers are used to see how the pattern how many times it will happen.
The {}, * and + signs are used to see this. For example the * in ``` /^w+([\.-]?\w+)*``` is checking that too. The {} is checking for ```w{2,3})+$``` more than 2 and less than 3 characters. Plus sign is looking for following words after that one.

### Grouping Constructs

Grouping uses parenthesis to capture substrings, so the ```([\.-]?\w+)``` is separated from ```*@\w+([\.-]?\w+)*```

### Bracket Expressions

The [] <-- Brackets is to group of the email strings, so the [\.-] in the code is that.

### Character Classes

Character classes is the "w" which is looking for word classes. 

### The OR Operator

There's no OR Operator here, but if there was, it would be the "|" symbol, and it would search for another specific string.

### Flags

There's no flags because flags are meant to detect any sensitivities such as caps locks and uppercases, for emails we shouldn't want this.

### Character Escapes

Character escapings are special characters, which you would need to use a backslash \ symbol, the code snippet has plenty of those for things like ".", "@", etc.

## Author

Singharaj Usai: https://github.com/singharaj-usai
Free Code Camp: https://www.youtube.com/watch?v=909NfO1St0A
