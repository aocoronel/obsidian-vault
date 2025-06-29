# Markdown

## Headings

```markdown
# H1 - F38BA8

## H2 - F3B387

### H3 - A6E3A1

#### H4 - 90E2D5

##### H5 - A0BEFE

###### H6 - CBA6F7
```

## Quotes

```markdown
> This is a callout
```

> This is a callout

## Blockquotes

```markdown
> [!note]
> This is a blockcallout
```

> [!note]
> This is a blockcallout

### Blockquotes Types

> [!tldr] Abstract, summary, tldr

> [!info]

> [!todo]

> [!tip] Tip, hint, important

> [!success] Success, check, done

> [!question] Question, help, faq

> [!warning] Warning, caution, attention

> [!failure] Failure, fail, missing

> [!danger] Danger, error

> [!bug]

> [!example]

> [!quote] Quote, cite

> [!note]

> [!faq]- Foldable Callouts
> Surprise!

## Text Decoration

```markdown
**Bold**
_Italic_
==Highlight==
~~strikethrough~~
^sup
```

**Bold**
_Italic_
==Highlight==
~~strikethrough~~
^sup

## Lists

```markdown
- Unordered list
  - Indented unordered list
  - Second line

1. Ordered list
   1. Indented ordered list
   2. Second line

- [ ] Task list
- [x] Completed task
```

- Unordered list
  - Indented unordered list
  - Second line

1. Ordered list
   1. Indented ordered list
   2. Second line

- [ ] Task list
- [x] Completed task

## Links

```markdown
[Link title](link url)
[DuckDuckGo](https://duckduckgo.com)
[Reference][1]
[1]: https://duckduckgo.com
[[Internal Link]]
```

[Link title](link url)
[DuckDuckGo](https://duckduckgo.com)
[Reference][1]
[1]: https://duckduckgo.com
[[Internal Link]]

## Inline Code and Code Blocks

```markdown
Inline `code`
Code Blocks have three backticks
```

Inline `code`

```python
print("Hello, World!")
```

# Tables

```markdown
Colons can be used to align columns.

| Table        |    Header    |              Text |
| ------------ | :----------: | ----------------: |
| Normal row   | Centered row | Right-aligned row |
| Row 2, Col 1 | Row 3, Col 2 |          **Bold** |
| Row 3, Col 1 | Row 3, Col 2 |          _Italic_ |
```

| Table        |    Header    |              Text |
| ------------ | :----------: | ----------------: |
| Normal row   | Centered row | Right-aligned row |
| Row 2, Col 1 | Row 3, Col 2 |          **Bold** |
| Row 3, Col 1 | Row 3, Col 2 |          _Italic_ |

# Horizontal Rules

```markdown
---
---
```

---

---

# Footnotes

```markdown
This is a simple footnote[^1].
[^1]: This is the referenced text.
[^2]: Add 2 spaces at the start of each new line. This lets you write footnotes that span multiple lines.
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.
```

## Latex

```latex
$$f(x) = \int_{-\infty}^\infty    \hat f(\xi)\,e^{2 \pi i \xi x}    \,d\xi$$
```

$$f(x) = \int_{-\infty}^\infty    \hat f(\xi)\,e^{2 \pi i \xi x}    \,d\xi$$
