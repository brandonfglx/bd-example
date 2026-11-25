# Heading 1 (H1)
## Heading 2 (H2)
### Heading 3 (H3)
#### Heading 4 (H4)
##### Heading 5 (H5)
###### Heading 6 (H6)

---

## Text Formatting & Emphasis

* **Bold text** using asterisks or __underscores__.
* *Italic text* using asterisks or _underscores_.
* ***Bold and italic text*** combined.
* ~~Strikethrough text~~ (GFM extension).
* Inline `code snippet` with backticks.
* Subscript H~2~O and Superscript X^2^ (extended syntax).
* ==Highlighted text== (extended syntax).

---

## Blockquotes

> This is a standard blockquote.
> 
> > This is a nested blockquote.
> > > And a third level of nesting.

---

## Lists

### Unordered List
* Item A
* Item B
  * Nested Item B.1
  * Nested Item B.2
    * Deeply nested Item B.2.a

### Ordered List
1. First item
2. Second item
   1. Sub-item 2.1
   2. Sub-item 2.2
3. Third item

### Task List (GFM)
- [x] Completed task
- [ ] Incomplete task
- [ ] Task with **formatting** and a [link](https://example.com)

---

## Links & Images

* **Inline Link:** [Visit Example](https://example.com "Optional Title")
* **Reference Link:** [Reference Link Text][ref-id]
* **Autolink:** <https://example.com>

[ref-id]: https://example.com "Reference Title"

**Image:**
![Alt text for placeholder image](https://placeholder.com "Image Title")

---

## Code Blocks

### Indented Code Block
    // 4 spaces indentation
    const x = 10;

### Fenced Code Block with NO Syntax Highlighting
```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
  return true;
}
greet("World");
```

---

## Tables (GFM)

| Left-Aligned | Center-Aligned | Right-Aligned |
| :--- | :---: | ---: |
| Row 1, Col 1 | Row 1, Col 2 | $100.00 |
| Row 2, Col 1 | `Inline Code` | $250.50 |
| **Bold Cell** | *Italic Cell* | $1,000.00 |

---

## Footnotes & Escaping

Here is a sentence with a footnote.[^1]

[^1]: This is the footnote content at the bottom.

**Escaped Characters:** \*Not italic\*, \# Not a heading, \[Not a link\].

---

## Horizontal Rules

***
---
___

---

## Inline HTML (If Supported)

<details>
<summary>Click to expand collapsible section</summary>
<p>Hidden content inside an HTML details tag.</p>
</details>
