---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'ER -> Relational ALgorithm'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

<h3>Step 1</h3>

* Create strong entity relations
* include atomic attributes and Choose Primary Key

<h3>Step 2</h3>

* Create weak entity relation
* Make the strong entity's primary key and the partial key both primary key
* Make the strong entity's primary key a foreign key to string entity


<h3>Step 3</h3>

* Map binary 1-to-1
* Use foreign key or Merge the relations ( if both are total)
* Foreign Key Method
	1. Choose one relation ( better if it is total)
	2. Add the primary key of the other relation as a foreign key.


<h3>Step 4</h3>

* Map binary 1-to-N
* Choose the many sides relationship 
* Add the other relations primary key as an foreign key
* Another approach is to create a relationship relation

<h3>Step 5</h3>

* Map Binary M-to-N
* Must create a new relation 
* Add both relations primary key's as foreign keys
* BOth relations primary key's together becomes the PK of the new relation.

<h3>Step 6</h3>

* Multivalued attributes
* Create a new relation
* Add as foreign keys the primary keys of the original relation
* All attributes forms the primary key



