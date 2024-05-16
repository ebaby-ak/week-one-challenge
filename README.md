# 01 HTML, CSS, and Git: Code Refactor

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
## Challenge Overview

This challenge offered the user starter code and a css sheet to begin. Upon opening the index.html you can see that many div tags are being used, this is not ideal for efficient viewing of this html by others. I began by replacing the div tags with semantic elements for the sections such as header, nav, section, and figure. These elements help describe what is going on in each part of the index.html sheet. In the css sheet, you can see that multiple selectors are being used that have the same attributes. To make this sheet more efficient, I consolidated the selectors that used the same attributes.