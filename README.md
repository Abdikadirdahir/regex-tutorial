# regex-tutorial

We'll take a quick look at what Regex "regular expressions" are and how they work in this tutorial. While regular expressions may appear intimidating at first appearance, they can be broken down into its most basic components and easily understood, much like any language.

-Summary 
A regular expression is a pattern that describes a set of characters. From left to right, it is matched against a subject string. The pattern /abc/, for example, only matches character combinations in strings when the identical sequence "abc" appears.

Table of content 

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

Anchors are regular expression characters that allow the user to match sequences that start or end with specific characters. The single-line mode is the default for the anchor ^ or $. The anchor  ^ and $ match the beginning and end of the input text in single-line mode.

### Quantifiers
Characters in the regular expression known as unatifiers determine how many times a character, group, or character class must appear in the input to be matched.

some examples of quantifiers are  

*	*?	Match zero or more times.
*	+?	Match one or more times.
*	??	Match zero or one time.
*	{ n }?	Match exactly n times.
* { n ,}?	Match at least n times.
*	{ n , m }?	Match from n to m times.
*	
### Grouping Constructs
The subexpressions of a regular expression are defined by grouping constructs, while the substrings of an input string are captured by grouping constructions.


### Bracket Expressions
Characters encompassed by a bracket [] match any single character within the brackets.

### Character Classes
Character Classes are Character Set instructs that the regex engine to match only one of a group of characters, such as numerals, words, or whitespace.

### The OR Operator
OR Operators The "Alternation Operator" matches one of several regular expressions: if the characters representing the alternation operator are placed between any two characters in a regular expression.

### Flags
optional flags in regular expressions enable features such as global and case-insensitive searches. These flags can be used individually or in any order, and they are incorporated in the regular expression.

### Character Escapes
Regular expression patterns recognize character escapes, whereas replacement patterns do not.
\	Backslash	Used to escape a special character
## Author

My name is Abdikadir Dahir, a student at sdsu, currently attending a full stack programing bootcamp at usdc, looking to expand my knowledge and became a front/back-end programmer.

``

