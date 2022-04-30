# Code Refactor Starter Code

# Module One Horiseon Accessibility Changes

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Changes Made For Accessibility

- Changed first container div to Header
- Changed div wrapping navigaition links to nav
- Changed styles sheet selector because chaning nav broke css
- Changed div after hero banner to article
- Changed each div in first article to section
- Changed next container div to article
- Changed all divs in second article to section
- Changed footer div to footer
