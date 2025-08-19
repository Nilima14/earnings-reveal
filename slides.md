---
marp: true
title: Product Documentation Presentation
author: Nilima Motghare
theme: default
paginate: true
---

<!-- _class: lead -->

# Product Documentation  
### Using Marp in GitHub Pages  

**Email:** 23f1000504@ds.study.iitm.ac.in  

---

# Why Marp?  

- Write presentations in **Markdown**  
- Version control friendly (Git + GitHub)  
- Export to **HTML, PDF, PPTX**  
- Use **custom themes & directives**  

---

# Custom Theme Example

<style>
section {
  background: #fdf6e3;
  color: #073642;
  font-family: "Segoe UI", sans-serif;
}
h1 {
  color: #b58900;
}
h2 {
  color: #cb4b16;
}
</style>

This slide uses a **custom theme** with Solarized colors 🎨

---

# Slide with Background Image

![bg cover](images/background.jpg)

Text appears on top of the background image.  
*(Place `background.jpg` inside `images/` folder in your repo)*

---

# Mathematical Example  

Algorithm complexity for Merge Sort:  

$$
T(n) = 2T\left(\frac{n}{2}\right) + O(n)
$$  

Simplifies to:  

$$
T(n) = O(n \log n)
$$

---

# Code Example

```python
def greet():
    print("Hello from Marp!")
