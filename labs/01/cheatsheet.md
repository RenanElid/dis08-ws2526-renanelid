# Lab 1 – Markdown Cheat Sheet

---

## Basic Formatting

### Headings
Headings use hash symbols (`#`) and have six levels.  
The more hashes, the smaller the heading.  
Example:  
`# Heading 1` → # Heading 1  
`## Heading 2` → ## Heading 2  

---

### Paragraphs & line breaks
A paragraph is made by writing normal text.  
To start a new line, add two spaces at the end or use `<br>`.  
Example:  
`This is one line.`  
`This is another.`  

---

### Bold
Used by wrapping a word with `**` or `__` to make it **bold**.  
Example:  
`**bold**` → **bold**

---

### Italic
Used by wrapping a word with `_` or `*` to make it *italic*.  
Example:  
`_italic_` → _italic_

---

### Strikethrough
Used to show text that is removed or wrong.  
Wrap the text with `~~`.  
Example:  
`~~this is wrong~~` → ~~this is wrong~~

---

### Inline code
Used to show short code or commands.  
Example:  
`` `print("Hello")` `` → `print("Hello")`

---


## Lists

### Unordered lists
Used to create bullet points.  
Write `-` or `*` before each item.  

Example:  
`- Apple`  
`- Banana`  
`- Orange`  

→  
- Apple  
- Banana  
- Orange  

---

### Ordered lists
Used for numbered steps.  
Write numbers followed by a dot.  

Example:  
`1. First`  
`2. Second`  
`3. Third`  

→  
1. First  
2. Second  
3. Third  

---

### Nested lists
Used when you need sub-items.  
Add two spaces before the sub-item.  

Example:  
`1. Main item`  
`   - Sub item`  
`   - Another sub item`  
`2. Second main item`  

→  
1. Main item  
   - Sub item  
   - Another sub item  
2. Second main item

---

## Links & Images

### Inline links
Used to add a link directly in the text.  
Write `[text](URL)`  

Example:  
`[TH Köln](https://www.th-koeln.de)`  

→  
[TH Köln](https://www.th-koeln.de)

---

### Reference-style links
Used when you want to keep links clean and separate from the text.  
You write a reference name and define the link later.  

Example:  
`[GitHub][1]`  
`[1]: https://github.com`  

→  
[GitHub][1]  
[1]: https://github.com

---

### Images
Used to show an image.  
Write `![alt text](image URL)`  

Example:  
`![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)`  

→  
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

### Image + link combination
Used to make an image clickable.  
You put the image markdown inside a link markdown.  

Example:  
`[![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)](https://github.com)`  

→  
[![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)](https://github.com)

---
## Tables

### Basic tables
Used to organize data in rows and columns.  
Use `|` for columns and `-` for the header line.  

Example:

```
| Name | Age |
|------|-----|
| Renan | 23 |
| Milena | 22 |
````

→

| Name   | Age |
| ------ | --- |
| Renan  | 23  |
| Milena | 22  |

---

### Alignment

You can align text to the left, center, or right.
Use `:` for alignment.

Example:

```markdown
| Left | Center | Right |
|:-----|:------:|------:|
| A | B | C |
```

→

| Left | Center | Right |
| :--- | :----: | ----: |
| A    |    B   |     C |

---

### Complex tables

You can use formatting like **bold** or *italic* inside cells.

Example:

```markdown
| Item | Description | Done |
|------|--------------|------|
| 1 | **Bold text** | ✓ |
| 2 | _Italic text_ | ✗ |
```

→

| Item | Description   | Done |
| ---- | ------------- | ---- |
| 1    | **Bold text** | ✓    |
| 2    | _Italic text_ | ✓    |

---

## Task Lists

### Checkboxes

Used to create to-do lists.
Write `- [ ]` for unchecked and `- [x]` for checked items.

Example:

```markdown
- [x] Write Lab 1
- [ ] Submit Lab 1
- [ ] Start Lab 2
```

→

* [x] Write Lab 1
* [ ] Submit Lab 1
* [ ] Start Lab 2



