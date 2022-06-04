# Regular Expression

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

Anchors are symbols at the beginning and end of a string like email code, /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
The caret ^ defines the beginning of the string. The dollar sign $ defines the end of the string.

### Quantifiers

Quantifiers indicate numbers of characters or expressions to match.

### OR Operator

The "OR" operator | is used when attempting to choose between mulitple characters

example) A|B means A or B

### Character Classes

Character classes defines a set of charaters of which occur in a string.

### Flags

Flags are addition feature in Regex which allow for advanced functionality. These can be used separately or together. A flag will cause the regex to search in a different way. There are 6 flags in JavaScript. They are i, g, s, m, y, and u.

### Grouping and Capturing

Grouping expressions allows us to keep things more organized and easier to exact the characters of a given group.
  - `(https?:\/\/)`
  - `([\da-z\.-]+)`
  - `([a-z\.]{2,6})`
  - `([\/\w \.-]_)`

### Bracket Expressions

Bracket expressions are used between brackets. 
example) [\da-z\.-], [a-z\.], [\/\w \.-]

### Greedy and Lazy Match

'Greedy' means matching the longest possible string. 
'Lazy' means matching the shortest possible string.

### Boundaries

Boundaries define where a match is taking place in a regex expression.
Boundaries are similar to an anchor and uses the expression \b for word boundaries and \B for non-word boundaries. The beginning of this expression \b([-a-zA-Z0-9()@:%_\+.~#?&//=]*) is searching for all word or digit.

### Back-references

Backreferences match the same text as previously matched by a capturing group.

### Look-ahead and Look-behind
Lookahead and lookbehind are called "lookaround", Lookbehinds are specific for groups that are before the pattern, and lookaheads are for groups after the pattern.

## Author
Hey Everyone! My name is Lee and I am learning computer coding at UCB Extension BootCamp. I would like to apply the tools I learn in HTML, CSS and JavaScript to attain a position Front End Developer. I like the idea of working with the visual side of browsers, and developing tools with how the user interacts with website. Here is my github <https://github.com/Jeongholee21>
