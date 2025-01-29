# Comprehensive Markdown Tutorial

Markdown is a lightweight markup language that’s easy to read and write. It’s widely used for formatting plain text,
such as documentation, README files, and even blog posts.

---

## Table of Contents

1. [Headings](#headings)
2. [Paragraphs](#paragraphs)
3. [Emphasis](#emphasis)
4. [Lists](#lists)
5. [Links](#links)
6. [Images](#images)
7. [Blockquotes](#blockquotes)
8. [Code](#code)
9. [Tables](#tables)
10. [Horizontal Rules](#horizontal-rules)
11. [Escaping Characters](#escaping-characters)
12. [Advanced Features](#advanced-features)

---

## Headings

Use `#` symbols to create headings. The number of `#` determines the heading level (1-6).

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

---
Result:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

### Paragraphs

Write plain text to create paragraphs. Leave a blank line between paragraphs

```markdown
This is a paragraph.

This is another paragraph.
```

Result:

This is a paragraph.

This is another paragraph.

---

### Emphasis

**Italics**
Wrap text in single asterisks (`*`) or underscores (`_`).

Result: *Italics*

```markdown
**Bold** or __Bold__
```

---

### Bold

Wrap text in double asterisks (`**`) or underscores (`__`).

```markdown
**Bold** or __Bold__
```

Result: **Bold**

---

### Bold and Italic

Combine three asterisks (`***`) or underscores (`___`).

```markdown
***Bold and Italic*** or ___Bold and Italic___
```

Result: *Italic*, **Bold**, ***Bold and Italic***

---

### Lists

**Unordered Lists**

Use `-`, `*`, or `+` followed by a space.

```markdown
- Item 1
- Item 2
    - Subitem 2.1
    - Subitem 2.2
```

Result:

- Item 1
- Item 2
    - Subitem 2.1
    - Subitem 2.2

**Ordered Lists**

Use numbers followed by a period (`.`).

```markdown
1. Item 1
2. Item 2
    1. Subitem 2.1
    2. Subitem 2.2
```

Result:

1. Item 1
2. Item 2
    1. Subitem 2.1
    2. Subitem 2.2

---

### Links

Use `[link text](url)` to create links.

```markdown
[OpenAI](https://www.openai.com)
```

Result: [OpenAI](https://www.openai.com)

---

### Images

Use `![alt text](url)` to add images.

```markdown
![Alt Text](https://example.com/image.jpg)
```

Result: ![Alt Text](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/OpenAI_Logo.svg/390px-OpenAI_Logo.svg.png)

---

### Blockquotes

Use `>` followed by a space to create blockquotes.

```markdown
> This is a blockquote.
> It spans multiple lines.
```

Result:

> This is a blockquote.
> It spans multiple lines.

---

### Code

**Inline Code**

Wrap text in backticks (`).

```markdown
Use the `printf` function in C.
```

Result: Use the `printf` function in C.

---

**Code Blocks**

Wrap code with triple backticks (```), optionally specifying a language for syntax highlighting.

<pre> ```python def greet(name): return f"Hello, {name}!" ``` </pre>

Result:

```python
def greet(name):
    return f"Hello, {name}!"
```

---

### Tables

Use `|` to create tables. Separate headers from rows with `---`.

```markdown
| Name     | Age | Occupation  |
|----------|-----|-------------|
| Alice    | 30  | Developer   |
| Bob      | 25  | Designer    |
```

Result:

| Name  | Age | Occupation |
|-------|-----|------------|
| Alice | 30  | Developer  |
| Bob   | 25  | Designer   |

---

### Horizontal Rules

Use three or more `---`, `***`, or `___`.

```markdown
---

***
___
```

Result:

---

***

---

### Escaping Characters

Use a backslash (`\`) to escape Markdown syntax.

```markdown
This is a \*literal asterisk\*.
```

Result: This is a *literal asterisk*.

---

### Advanced Features

**Task Lists**

Use `- [ ]` for an unchecked box and `- [x]` for a checked box.

```markdown
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

Result:

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

**Footnotes**

Use `[^1]` followed by a space to create footnotes.

```markdown
This is a sentence with a footnote.[^1]

[^1]: This is the footnote text.
```

Result:

This is a sentence with a footnote.[^1]

[^1]: This is the footnote text.

**Strikethrough**

Wrap text with ~~ to strike through.

```none
~~strikethrough~~
```

Result: ~~Strikethrough~~

### Even more advanced features

**Definition Lists**

Create terms and definitions using a colon and indentation.

```markdown
Term 1:
: Definition for Term 1

Term 2:
: Definition for Term 2
```

Result:

Term 1:
: Definition for Term 1

Term 2:
: Definition for Term 2

**Admonitions (Custom Callouts)**

Use `!!!` to create custom callout blocks (used in some Markdown parsers like MkDocs).

```markdown
!!! note
    This is a note with a default color.

!!! warning
    This is a warning in orange or red.

!!! success
    This is a success message in green.

```

Result:

!!! note
This is a note with a default color.

!!! warning
This is a warning in orange or red.

!!! success
This is a success message in green.

---