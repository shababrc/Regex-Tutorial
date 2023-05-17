# Regex-Tutorial

## Description
A tutorial that explains how a specific regular expression, or regex, in this case a regex pattern to match a URL, functions by breaking down each part of the expression and describing what it does.

## User Story
``
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
``
## Acceptance Criteria
``
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile
``

## How We Did This:
### By:
The regex expression is as follows:
This regular expression pattern validates and extracts URLs in an application. The pattern is as follows:
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
We first destructure the pattern according to what we research,
we destructure and describe what the anchors were, the quantifiers, the or-operator, the character-classes, the flags, the grouping and capturing, the greedy and lazy match, the back references and boundaries, and the look ahead and look behind. We explain what each of these components serves to the pattern, and determine what they mean or represent in the URL regex expression matching pattern.

## Link to Github Repository
https://github.com/shababrc/Regex-Tutorial 

## Link to the Gist


## Credits
Big thanks to the rest of the bootcamp class for their help, as well as Bryan and Shawn for their expertise.

## License
MIT