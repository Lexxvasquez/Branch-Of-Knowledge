# Branch-Of-Knowledge

## Summary

In this assignment I gave a short description and examples for each term that is used in Regex.

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
A regular expression (shortened as regex or regexp; sometimes referred to as rational expression)
is a sequence of characters that specifies a match pattern in text. Usually such patterns are used
by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

### Anchors
Anchors belong to the family of regex tokens that don't match any characters,
but that assert something about the string or the matching process.

### Quantifiers
Quantifiers allow you to specify the number of occurrences of a character or
group, making it easier to match patterns of varying lengths.

### OR Operator
 Common Operators

 Operator                      Description                        Example 

 .                Matches any character as a wildcard                a.c
 |                            An OR character                      abc|xyz
 (...)              Captures values in the parenthesis             (a)b(c)
 [...]              Matches anything within the brackets            [abc]

### Character Classes
In the context of regular expressions, a character class is a set of
characters enclosed within square brackets. It specifies the characters that
will successfully match a single character from a given input string.

### Flags
It's not +$ but [a-zA-Z]+ and then $ . $ means end of line. + means one or more
occurrences of the preceding pattern ( [a-zA-Z] ).

### Grouping and Capturing
Capturing in regexps means indicating that you're interested not only in matching
(which is finding strings of characters that match your regular expression),
but you're also interested in using specific parts of the matched string later on.

### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall 
match a specific set of single characters, and may match a specific set of multi-character 
collating elements, based on the non-empty set of list expressions contained in the bracket expression.

### Greedy and Lazy Match
Greedy matching is the default behavior of regular expressions, where the regular expression engine will try to match as much text as possible. In contrast, non-greedy matching, also known as lazy matching, tries to match as little text as possible.

### Boundaries
Boundary markers such as ^ and $ allow you to anchor the regex pattern to the beginning and end of the line (or string depending on which flags you use) respectively. This means that when you want to match a literal ^ or $ , you need to escape these special characters with a backslash.

### Back-references
back-references are regular expression commands which refer to a previous part of the matched regular expression. Back-references are specified with backslash and a single digit (e.g. ' \1 '). The part of the regular expression they refer to is called a subexpression, and is designated with parentheses.

### Look-ahead and Look-behind
A lookahead assertion "looks ahead": it attempts to match the subsequent input with the given pattern, but it does not consume any of the input — if the match is successful, the current position in the input stays the same.

A negative lookbehind assertion asserts true if the pattern inside the lookbehind is not matched. For example, (? <! xyz)abc asserts that there cannot be the string, xyz , just before matching the string, abc.

## Author
My name is Alexis. I was born and raised in the Sunshine State! I love spending time with my German Shepherd and Bichon Frise on days off! I work full time and currently enrolled in University of Central Florida FullStack Bootcamp as a parttime student. I'm looking forward to the new career change and learning more
things in this field! 

Lexx Vasquez
E: lexx.sunshineteam@gmail.com
P: 000.000.0000

https://gist.github.com/Lexxvasquez/81c3f1c5fe73de12d1bb13b55c3b4d76

https://github.com/Lexxvasquez/Branch-Of-Knowledge




