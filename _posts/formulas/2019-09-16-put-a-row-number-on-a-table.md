---
Title: "Put a Row Number on a Table"
layout: single
categories:
  - formulas
tags:
  - tables
date: 2019-09-16 18:43:00
sidebar:
  title: "Popular Links"
  nav: sidebar-sample
---

Here's a simple way to get the row number of the table items.  
It's a simple formula referencing the current cell’s row minus the row number of the table header row.  

In this example I've kept the table name as Table1
```vb
=ROW()-ROW(MyTable[[#Headers],[Row '#]])
```

![table-row-number-img](/imgs/table-row-number/table-row-number.png)
