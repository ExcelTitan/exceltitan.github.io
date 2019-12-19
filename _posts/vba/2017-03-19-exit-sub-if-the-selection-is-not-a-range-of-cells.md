---
Title: "Exit Sub if the Selection is Not a Range of Cells"
layout: single
classes: wide
categories:
  - vba
tags:
  - developer
date: 2017-03-19 18:43:00
sidebar:
  title: "Popular Links"
  nav: sidebar-sample

---


This code snippet is useful to check if the selection is a range of cells.

```vb
If TypeName(Selection) <> "Range" Then Exit Sub
```
