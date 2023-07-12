# Title (Match Hex Values)

For this assignment

## Summary
I am explaining the regex components ^#?([a-f0-9]{6}|[a-f0-9]{3})$/.
Regex also known as regular expression are used to describe patterns It can be used to locate and validate a multitude of charachter types and inputs. There are many uses for Regular expressions and can be seen throughout code as an almost short cut to make the coders life a little easier and complete the desired task.


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
for this Regex there are 2 Anchors ^ known as Caret is used to match the beginning of a line. $ known as dollar sign is used to match the end of a line. what Anchors do is they match positions. 
### Quantifiers
For this Regex there are several qualifiers the first of which is the ?. ? matches 0 or 1 preceding character. you can also see the use of {} this allows you to create an exact numarical range, so for this it would be 6. 
### Grouping Constructs
constructs are () and allow the developer to match everything inside of them. This can be usefull to diferenciate subexpressions inside a regex 
### Bracket Expressions
bracket expression [] are used to create a character group or range similar to the parentheses. they are used to group expressions and characters. 
### Character Classes
Character classes are used to diferenciate characters they can be spotted because they will be surounded by squaire brackets []. this allows you to match charachters from a specifig string 
### The OR Operator
The OR Operator are used to match 2 different patterns together an allows the user to match them together for example when we look at the expression [a-f0-9]{6}|[a-f0-9] it is matching [a-f0-9]{6} | and [a-f0-9]{3}
### Flags
Flags are optional parameters, it modifies ahd changes the behavior of searching. a flag can be seen and is represented by a lowercase letter such as a and f in this code.
### Character Escapes
Character Escapes can be used for metacharacters or like the name says escape regex characters. you can also see this comonly used in \n which represents new line.
## Author
Alex Watabe