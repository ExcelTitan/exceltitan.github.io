---
Title: "Check if a cell Contains Specific Text"
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

## How it Works Using SEARCH and ISNUMBER
When you need to check if a cell contains specific text (or string) we need to combing the SEARCH and ISNUMBER functions. The SEARCH function will give us the starting position of the text you're trying to find, when that is wrapped in the ISNUMBER function we will end up with a TRUE or FALSE.

## Generic formula 
```vb
' syntax
=ISNUMBER(SEARCH(text_to_search_for, within_text))

' if cell contains example
=IF(ISNUMBER(SEARCH(text_to_search_for, within_text)), "Yes", "No")
```

In the example shown, the formula in D5 is:
```vb
=ISNUMBER(SEARCH(C5,B5))
```

![Check-if-a-cell-contains-specific-text](/imgs/Check-if-a-cell-contains-specific-text/Check-if-a-cell-contains-specific-text.png)

## Problems with Countif
Testing if a cell contains specific text is a bit tricky, you'd think to use Countif but that's a no go for text.



