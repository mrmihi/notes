---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'What is Group-by'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

<blockquote>If the SELECT expression contains a GROUP BY-clause, it must appear after the WHERE clause. 
(If the WHERE clause is omitted, the GROUP BY clause will immediately follow after the FROM clause.)
<br><br>
When included, GROUP BY specifies that rows from the intermediate result set are to be divided in a number of groups, 
returning one single row for each such group. The list of expressions provided in the GROUP BY list defines how the grouping takes place.
All rows that have the same combination of values for all expressions specified in the GROUP BY are in the same group.
<br><br>
At a glance, it seems as if the GROUP BY clause does nothing more than scan for unique occurrences in the column(s) in the GROUP-BY clause and return those. However, 
it is better to think of each row in the GROUP BY result as a <em><strong>summary row</strong></em> that represents a group of rows that have the same value in the species column.
<br><br>
A GROUP BY query allows one to apply aggregate functions on the collection of rows associated with each group defined by the GROUP BY clause.
An aggregate function can process expressions for each row in a group of rows to compute a single return value. 
A number of well-known standard aggregate functions are COUNT, MIN, MAX, and SUM. </blockquote>

<em><strong>think of each row in the GROUP BY result as a summary row that represents a group of rows that have the same value in the column that's specified in the GROUP-BY clause.</strong></em>

<a href='https://rpbouman.blogspot.com/2007/05/debunking-group-by-myths.html' target = '_blank' > REFERENCE </a>






