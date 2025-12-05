<!--
Source - https://stackoverflow.com/a/42876643
Posted by Morgoth, modified by community. See post 'Timeline' for change history
Retrieved 2025-11-30, License - CC BY-SA 3.0
-->

<h1 align="center">Dev Dictionary</h1>
<p align="center">Find information on any technology</p>
<kbd><img src="https://cloud.githubusercontent.com/assets/4705188/20508600/ac62b414-b030-11e6-9dfe-691a6a3250fd.png" alt="image">
</kbd>

## Overview

This is the repository of **Dev Dictionary**, a Chrome Extension to help developers find information on any technology. It can be installed through the [Chrome Web Store](https://chrome.google.com/webstore/detail/dev-dictionary/mbhildcgplbobgnhgnihmeiaokhdaelf).

## Development

- For more information regarding development of Chrome extensions, see [Getting Started: Building a Chrome Extension](https://developer.chrome.com/extensions/getstarted)
- For more information regarding Chrome extension APIs, see [Chrome Platform APIs](https://developer.chrome.com/extensions/api_index)

## Libraries

- [React ](https://facebook.github.io/react/)
- [Redux ](http://redux.js.org/)
- [Webpack](https://webpack.github.io/)
- [Node JS](https://nodejs.org)
- [Bootstrap](http://getbootstrap.com/)
- [jQuery](https://jquery.com/)

# Markdown syntax guide

## Headers

# This is a Heading h1

## This is a Heading h2

###### This is a Heading h6

## Emphasis

_This text will be italic_  
_This will also be italic_

**This text will be bold**  
**This will also be bold**

_You **can** combine them_

## Lists

### Unordered

- Item 1
- Item 2
- Item 2a
- Item 2b
  - Item 3a
  - Item 3b

### Ordered

1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

## Images

![This is an alt text.](/image/sample.webp "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
> > Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns | Right columns |
| ------------ | :-----------: |
| left foo     |   right foo   |
| left bar     |   right bar   |
| left baz     |   right baz   |

## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.
