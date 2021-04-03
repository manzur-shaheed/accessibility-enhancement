# accessibility-enhancement (code refactored by Manzur Shaheed)

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
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Solution

* WHEN I view the source code 
THEN I find semantic HTML elements
Semantic elements **header**, **nav**, **main**, **section**, **figure**,  **footer** and comments are inserted into this html page for better readability and maintenance.
&nbsp;

* WHEN I view the structure of the HTML elements 
THEN I find that the elements follow a logical structure independent of styling and positioning
This page has 3 top level elements **header**, **main** and **footer**.  **header** has **nav**, **main** has few **section** and **section** has **figure**.
&nbsp;

* WHEN I view the image elements
THEN I find accessible alt attributes
**img** elements have both **alt** and **title** attributes.
&nbsp;

* WHEN I view the heading attributes
THEN they fall in sequential order
They are in sequential order **h1** is before **h2**.
&nbsp;

* WHEN I view the title element
THEN I find a concise, descriptive title
Page has a **title** element and also a **meta** data **description** with a short description about the page.