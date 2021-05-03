---
Title: "Test a Cell Contains Specific Text"
layout: single
classes: wide
categories:
  - formulas
tags:
  - text
date: 2021-05-03
sidebar:
  title: "Popular Links"
  nav: sidebar-sample

---

Testing if a cell contains specific text is a bit tricky, you'd think to use Countif but that's a no go for text.

## Generic formula 
```vb
' syntax
=ISNUMBER(SEARCH(substring,text))
```
