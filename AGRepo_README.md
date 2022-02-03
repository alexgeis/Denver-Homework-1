# Denver-Homework-1 - Code Refactoring Assignment

## Description of Assignment

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular homework assignment, a marketing agency has hired you to refactor an existing site to make it more accessible. 

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Description of Updates

For this assignment I first went through the HTML and updated the elements to be more semantic.
I also added alt attributes to all image elements (include the hero image), and corrected ID/class groupings for the CSS file and anchor links.

Then, I went through the CSS and labeled the functions (or lack of) within the current code.

There were many CSS redundancies, so I refactored those into consolidated classes and commented out the depracated code. I applied my new classes and ensured the float properties were correctly affecting the onscreen elements.

## Links to final screenshot and github repo

[link to finished refactor assignment IMAGE - Alex Geis](./assets/images/01-html-css-git-homework_Alex-Geis_2.3.22.png)

[link to finished refactor assignment REPO - Alex Geis](https://alexgeis.github.io/Denver-Homework-1/)
