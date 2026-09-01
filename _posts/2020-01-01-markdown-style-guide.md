---
layout: post
title: Markdown Style Guide
date: 2020-01-01
---

This is a demonstration of all the markdown styling features available on this blog.

## Headings

### H3 Heading

#### H4 Heading

## Paragraphs

This is a regular paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

This is another paragraph with **bold text** and *italic text* and ***bold italic***. You can also use ~~strikethrough~~.

## Links

[This is a link](https://example.com)

## Lists

### Unordered List

- First item
- Second item
- Third item
  - Nested item
  - Another nested item
- Fourth item

### Ordered List

1. First step
2. Second step
3. Third step
   1. Nested step
   2. Another nested step
4. Fourth step

## Blockquotes

> "This is a blockquote. It can span multiple lines."
> 
> "And it can have multiple paragraphs."
>
> -- Author

## Code

Inline code: `const x = 42;`

### Code Block

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
  return true;
}

const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map(n => n * 2);

greet('World');
```

### Code Block with Language

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

for i in range(10):
    print(fibonacci(i))
```

```bash
#!/bin/bash
echo "Hello, World!"
ls -la
```

```rust
fn main() {
    let message = "Hello, Rust!";
    println!("{}", message);
}
```

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |
| Cell 7   | Cell 8   | Cell 9   |

## Horizontal Rule

---

## Images

![Alt text](https://via.placeholder.com/400x200)

## Emphasis

- **Bold text**
- *Italic text*
- ***Bold italic***
- ~~Strikethrough~~
- `Inline code`

## Task Lists

- [x] Completed task
- [ ] Incomplete task
- [ ] Another task

## Conclusion

That's all, Thank you for reading!
