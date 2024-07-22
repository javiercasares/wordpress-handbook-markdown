# WordPress Handbook Markdown _Quick Reference_

This cheatsheet provides a quick reference for [Markdown syntax](https://spec.commonmark.org/current/), making it easier to create and edit documents on GitHub.

It is designed for the _WordPress Community Handbooks_, therefore the options have been limited to a standard so that everyone does it as similarly as possible.

## Headers

The H1 only must be used on the page title.

```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

View the [example](example-headers.md).

## Emphasis

```markdown
_Italic text_
**Bold text**
**_Bold and italic text_**
~~Strikethrough text~~
```

View the [example](example-emphasis.md).

## Lists

```markdown
- Unordered list item
- Unordered list item

1. Ordered list item
2. Ordered list item
```

Lists with nested elements:

```markdown
* Item 1
* Item 2
* Item 3
    * Item 3.1
    * Item 3.2
    * Item 3.3

1. Item 1
2. Item 2
3. Item 3
    1. Item 3.1
    2. Item 3.2
    3. Item 3.3

1. Item 1
2. Item 2
3. Item 3
    * Item 3.1
    * Item 3.2
    * Item 3.3
```

View the [example](example-lists.md).

## Links

```markdown
[Link text](https://example.com "Optional title")
```

Links with code:

```markdown
[`function()`](https://example.com/function "Function name")
```

View the [example](example-links.md).

## Images

```markdown
![Alternative text](https://example.com/image.jpg "Optional title")
```

View the [example](example-images.md).

## Code

```markdown
`Inline code`
```

~~~markdown
 ```
 Code block
 ```
~~~

View the [example](example-code.md).

## Blockquotes

```markdown
> This is a blockquote.
> 
> This is a continuation of the blockquote.
```

View the [example](example-blockquote.md).

## Tables

```markdown
| Header 1 | Header 2 | Header 3 |
| -------- |:--------:| --------:|
| Text     | Text     | Text     |
| More text| More text| More text|
```

View the [example](example-tables.md).

## Horizontal Lines

```markdown
---
```

View the [example](example-horizontallines.md).

## Task Lists

This **only works in GitHub**. Shouldn't be use in documentation.

```markdown
- [ ] Pending task
- [x] Completed task
```

## Emojis

```markdown
:emoji_name:
```
You can find a complete list of supported emojis [here](https://github.com/ikatyang/emoji-cheat-sheet).

## Formatting (exclusive for WP.org Meta / P2)

### Info box

The blue box.

```markdown
[info]Some text.[/info]
```

### Tip box

The green box.

```markdown
[tip]Some text.[/tip]
```

### Alert box

The yellow box.

```markdown
[alert]Some text.[/alert]
```

### Warning box

The red box.

```markdown
[warning]Some text.[/warning]
```

### Tutorial box

The purple box.

```markdown
[tutorial]Some text.[/tutorial]
```

### PHP box

Usually is not needed. A Code block shold be fine.

```markdown
[php]<?php echo 'Hello World'; ?>[/php]
```

### HTML box

```markdown
[html]<abbr title="World Wide Web Consortium">W3C</abbr>[/html]
```

## Other helpers

### Arrows

- →
- ←
- ↑
- ↓
- ↔
- ↕
