# CTM website

Portal with a directory of legal resources and community contacts.

## Updating content

The homepages can be edited by opening the language-specific `index.md` files in `_homepage`.
- To make immediate changes, click the `Edit this file` button. 
- Content is written in Markdown. [Here's a 2-page PDF that contains syntax examples](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf). 

To add more pages, create Markdown files within `_pages/en` and `_pages/es`. Within each file, add this:

```markdown
---
lang-ref: my-new-page
title: <!-- sets the window title -->
description: <!-- displays text below logos, overrides the site description used in search results -->
subhead: <!-- displays text below logos, doesn't override the site description -->
---

Hello, world!
```

`lang-ref` allows users to stay on the page and switch languages.
