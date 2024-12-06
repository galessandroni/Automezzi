# Markdown Basic Syntax

Markdown is a lightweight markup language that you can use to add formatting to plain text. It's widely used for documentation, content management systems, and as a writing tool for developers.

This handbook provides an overview of the key syntax elements in Markdown to help you create well-formatted text quickly and efficiently.

## Table of Contents
1. [Headings](#headings)
2. [Text Formatting](#text-formatting)
3. [Lists](#lists)
4. [Links](#links)
5. [Images](#images)
6. [Code](#code)
7. [Blockquotes](#blockquotes)
8. [Tables](#tables)
9. [Horizontal Rules](#horizontal-rules)
10. [Task Lists](#task-lists)
11. [Inline HTML](#inline-html)
12. [Alerts](#alerts)

---

## Headings

Markdown uses `#` symbols for headings. The number of `#` symbols determines the heading level (1-6).

### Syntax

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

### Example:

# Heading 1  
## Heading 2  
### Heading 3  

---

## Text Formatting

You can format text in several ways using Markdown.

### Bold Text

Use `**` or `__` to make text bold.

### Syntax

```markdown
**bold text**
__bold text__
```

### Example:

**bold text**  
__bold text__

---

### Italic Text

Use `*` or `_` to make text italic.

### Syntax

```markdown
*italic text*
_italic text_
```

### Example:

*italic text*  
_italic text_

---

### Strikethrough Text

Use `~~` to strike through text.

### Syntax

```markdown
~~strikethrough text~~
```

### Example:

~~strikethrough text~~

---

## Lists

Markdown supports both ordered (numbered) and unordered (bulleted) lists.

### Unordered Lists

Use `-`, `+`, or `*` to create unordered lists.

### Syntax

```markdown
- Item 1
- Item 2
    - Subitem 1
    - Subitem 2
```

### Example:

- Item 1  
- Item 2  
    - Subitem 1  
    - Subitem 2  

---

### Ordered Lists

Use numbers followed by a period to create ordered lists.

### Syntax

```markdown
1. First item
1. Second item
    1. Subitem 1
    1. Subitem 2
```

### Example:

1. First item  
1. Second item  
    1. Subitem 1  
    1. Subitem 2  

---

## Links

You can add links using the following syntax:

### Syntax

```markdown
[Link Text](https://example.com)
```

### Example:

[Link Text](https://example.com)

You can also add a title that appears when the user hovers over the link.

```markdown
[Link Text](https://example.com "Title Text")
```

---

## Images

Images are similar to links but with an exclamation mark `!` before the link.

### Syntax

```markdown
![Alt Text](http://example.com/image.jpg)
```

### Example:

![Sample Image](https://via.placeholder.com/150)

---

## Code

Markdown allows you to include code in different formats.

### Inline Code

Use backticks `` ` `` for inline code.

### Syntax

```markdown
`inline code`
```

### Example:

`inline code`

---

### Code Blocks

Use triple backticks (``````) or indentation with four spaces for code blocks.

### Syntax

<pre>
```markdown
Code block
Line 2 of code
```
</pre>

### Example:

```markdown
Code block
Line 2 of code
```

---

## Blockquotes

You can create blockquotes using the `>` symbol.

### Syntax

```markdown
> This is a blockquote.
```

### Example:

> This is a blockquote.

---

## Tables

Markdown supports tables using `|` to separate columns and `-` to separate headers.

### Syntax

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

### Example:

| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |

---

## Horizontal Rules

Use three hyphens (`---`), asterisks (`***`), or underscores (`___`) to create a horizontal rule.

### Syntax

```markdown
---
```

### Example:

---

---

## Task Lists

Markdown also supports task lists using `- [ ]` for incomplete tasks and `- [x]` for completed tasks.

### Syntax

```markdown
- [ ] Task 1
- [x] Task 2
```

### Example:

- [ ] Task 1
- [x] Task 2

---

## Inline HTML

In some cases, you may need to use HTML within Markdown. You can mix HTML tags with Markdown.

### Example:

```markdown
<p>This is a paragraph using HTML tags.</p>
```

---

---

## Alerts

**Alerts** are an extension of Markdown used to emphasize critical information.
They are displayed with distinctive colors and icons to indicate the importance of the content.

```markdown
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```
**Here is how they are displayed:**

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

---

## Conclusion

Markdown is a simple yet powerful tool for formatting text in a readable and structured way. This handbook covers the core syntax elements, but there are many other advanced techniques and extensions available in various Markdown parsers.

Happy writing!
