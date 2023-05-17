# Regex URL Pattern Tutorial

A tutorial that explains how a specific regular expression, or regex, in this case a regex pattern to match a URL, functions by breaking down each part of the expression and describing what it does.

## Summary

A tutorial that explains how a specific regular expression, or regex, in this case a regex pattern to match a URL, functions by breaking down each part of the expression and describing what it does.

This regular expression pattern validates and extracts URLs in an application. The pattern is as follows:
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/


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
The ^ and $ symbols denote the start and end of the string, respectively. This ensures that the entire string matches the URL pattern.

### Quantifiers
The ? and * symbols are quantifiers used in this pattern.

(https?:\/\/)? matches the optional "http://" or "https://" protocol part of the URL. The ? makes the preceding group optional.
([\/\w \.-]*)* matches optional path segments separated by slashes, including alphanumeric characters, spaces, dots, or hyphens. The * allows for zero or more occurrences of this group.

### OR Operator
The | symbol is the OR operator. It is not present in this particular pattern.

### Character Classes
[\da-z\.-]+ matches one or more alphanumeric characters, dots, or hyphens in the domain name. The character class [\da-z\.-] includes digits (\d), lowercase letters (a-z), dots (\.), and hyphens (-).

### Flags
There are no flags used in this pattern.

### Grouping and Capturing
The pattern uses grouping to capture different parts of the URL. For example:

(https?:\/\/)? captures the protocol part of the URL.
([\da-z\.-]+) captures the domain name.
([a-z\.]{2,6}) captures the top-level domain (e.g., com, org, co.uk).
([\/\w \.-]*)* captures optional path segments.

### Bracket Expressions
Bracket expressions are used to define character classes in the pattern. For example:

[\da-z\.-] matches any digit, lowercase letter, dot, or hyphen.
### Greedy and Lazy Match
There are no explicit greedy or lazy quantifiers used in this pattern.

### Boundaries
There are no explicit boundaries used in this pattern.

### Back-references
There are no back-references used in this pattern.

### Look-ahead and Look-behind
There are no look-ahead or look-behind assertions used in this pattern.

Author: 
Shabab Chowdhury wrote this tutorial for explaining the regex pattern on URL matching. His github is 

