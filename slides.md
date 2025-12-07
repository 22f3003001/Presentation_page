---
marp: true
title: Product Documentation Presentation
paginate: true
theme: custom
style: |
  section {
    font-family: 'Segoe UI', sans-serif;
  }
  h1 {
    color: #005bbb;
    border-bottom: 3px solid #005bbb;
    padding-bottom: 8px;
  }
  .email {
    font-size: 0.9em;
    color: #444;
  }
---


<!--
Custom theme defined using Marp CSS variables
-->
<style>
:root {
  --color-background: #ffffff;
  --color-foreground: #222222;
  --color-primary: #005bbb;
  --color-secondary: #ffaa00;
  --heading-color: var(--color-primary);
}
</style>

# Product Documentation  
### Using Marp for Maintainable Tech Docs

<div class="email">Contact: 22f3003001@ds.study.iitm.ac.in</div>

---

# Overview

- Why Marp?
- Documentation workflow
- Version control integration
- Exporting to PDF / HTML / PPTX
- Custom themes & styling
- Mathematical notation support

---

<!-- Slide with Background Image -->
<!-- Replace with any image in your repo -->
<!-- Example uses Unsplash image -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1400&q=60)

# System Architecture  
### Visual Overview  
*(Background Image Slide)*

---

# Mathematical Example  

Marp supports **KaTeX**, allowing complex technical notation:

**Time complexity example**:

\[
T(n) = T(n-1) + T(n-2)
\]

Worst-case growth:

\[
T(n) = O(\varphi^n)
\quad\text{where}\quad
\varphi = \frac{1+\sqrt{5}}{2}
\]

Another example:

\[
O(n \log n)
\]

---

# Code Example

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
