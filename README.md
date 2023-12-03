# WordPress Handbook Markdown _Quick Reference_

This cheatsheet provides a quick reference for Markdown syntax, making it easier to create and edit documents on GitHub.

It is designed for the WordPress Community Handbooks, therefore the options have been limited to a standard so that everyone does it as similarly as possible.

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

## Emphasis

```markdown
_Italic text_
**Bold text**
**_Bold and italic text_**
~~Strikethrough text~~
```

## Lists

```markdown
- Unordered list item
- Unordered list item

1. Ordered list item
2. Ordered list item
```

## Links

```markdown
[Link text](https://example.com "Optional title")
```

Links with code:

```markdown
[`function()`](https://example.com/function "Function name")
```

## Images

```markdown
![Alternative text](https://example.com/image.jpg "Optional title")
```

## Code

```markdown
`Inline code`
```

~~~markdown
 ```
 Code block
 ```
~~~

## Blockquotes

```markdown
> This is a blockquote.
> 
> This is a continuation of the blockquote.
```

## Tables

```markdown
| Header 1 | Header 2 | Header 3 |
| -------- |:--------:| --------:|
| Text     | Text     | Text     |
| More text| More text| More text|
```

## Horizontal Lines

```markdown
---
```

## Task Lists

```markdown
- [ ] Pending task
- [x] Completed task
```

## Emojis

```markdown
:emoji_name:
```
You can find a complete list of supported emojis [here](https://github.com/ikatyang/emoji-cheat-sheet).

## Formatting

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

```markdown
[php]<?php echo 'Hello World'; ?>[/php]
```

### HTML box

```markdown
[html]<abbr title="World Wide Web Consortium">W3C</abbr>[/html]
```
## Arrows

- →
- ←
- ↑
- ↓
- ↔
- ↕
