---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Group By ^^ Select'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---

<hr>

>"SQL92 states that any non-aggregate expressions appearing in the SELECT-list must appear in the GROUP BY-clause. SQL99 and on state that any non-aggregate expressions that appear in the SELECT-list must be functionally dependent upon the list of expressions appearing in the GROUP BY. In this context, "functionally dependent" simply means that for each unique combination of values returned by the expressions that make up the GROUP BY-clause, the non-aggregate expression necessarily yields exactly one value."  

<br>

>A simpler way to say this is that given the list of expressions in the GROUP BY clause then there must be only one value for the non-aggregate expressions on the SELECT clause. <br>

<br>

>eg: grouping by a primary key will allow the usage of all other columns in the SELECT clause</p> 
  
  <br>

  <a href = 'https://rpbouman.blogspot.com/2014/09/mysql-575-group-by-respects-functional.html'>REFERENCE<a>
