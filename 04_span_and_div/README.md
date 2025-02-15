# README: Understanding `<span>` vs `<div>` in HTML

## Introduction
In HTML, `<span>` and `<div>` are both container elements used for structuring content. However, they serve different purposes and are used in different contexts. This document explains their differences, usage, and best practices.

## Key Differences

| Feature  | `<span>`  | `<div>`  |
|----------|----------|----------|
| Type | Inline element | Block-level element |
| Purpose | Used to style or manipulate small portions of text | Used to group larger sections of content |
| Line Breaks | Does not create a new line | Creates a new line before and after |
| Styling | Commonly used for styling words or phrases with CSS | Commonly used for layout structuring and grouping elements |

## Usage Examples

### 1. `<span>` Example
The `<span>` element is used for styling or scripting within a line of text:

```html
<p>This is a <span style="color: red; font-weight: bold;">highlighted</span> word.</p>
```

**Output:**
This is a **highlighted** word. (with red and bold styling)

### 2. `<div>` Example
The `<div>` element is used for structuring a block of content:

```html
<div style="background-color: lightgrey; padding: 10px;">
    <h2>Welcome</h2>
    <p>This is a block of content inside a `div`.</p>
</div>
```

**Output:**
A grey box containing a heading and a paragraph.

## When to Use Which?

- Use `<span>` when you need to apply styles or scripts to part of a sentence.
- Use `<div>` when you need to group multiple elements together, especially for layout purposes.

## Best Practices

- Avoid using `<div>` for inline text modifications—use `<span>` instead.
- Use `<div>` for layout structuring, especially when working with CSS and JavaScript.
- Keep semantic HTML in mind and use elements like `<section>`, `<article>`, and `<header>` when more appropriate.

## Conclusion

Understanding the difference between `<span>` and `<div>` helps in writing cleaner, more maintainable HTML. Use `<span>` for inline styling and `<div>` for block-level grouping of elements.


