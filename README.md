# CTM website

Portal with a directory of legal resources and community contacts.

## Updating content

The homepages can be edited by opening the language-specific `index.md` files in `_homepage`.
- To make immediate changes, click the `Edit this file` button. 
- Content is written in Markdown. [Here's a 2-page PDF that contains syntax examples](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf). 

To add more pages, create a Markdown file named `_pages/en/my-new-page`. Add this to it:

```markdown
---
lang-ref: my-new-page
title: <!-- sets the window title -->
description: <!-- displays text below logos, overrides the site description used in search results -->
subhead: <!-- displays text below logos, doesn't override the site description -->
---

Hello, world!
```

Ready to translate `my-new-page`? Create another file named `_pages/es/mi-nueva-pagina` and use the same `lang-ref`.
