---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Recursive Relationships'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

-A and AA <br> 
-one-to-many

<br>
A (<u>A's PK</u>, A's attributes)

<br>

AA (<u>A's PK</u>, AA's attributes)

<br>

<strong>After schema combination </strong>

<br>

`A ([A's PK], A's attributes, As's attributes )` 

<br>

-A and AA 
<br>
-many-to-many
<br>
<br>
`A (A's PK, A's attributes)`
<br>
`AA ([A's PK, AA's Candidate key], AA's attributes)`
