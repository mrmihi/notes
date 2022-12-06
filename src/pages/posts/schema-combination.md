---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Schema Combination'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

 Schema combination allows loss less compression, which will eliminate a foreign key contraints, reduce storage requirements and enforce constraints.

Unnecessary compression might require the usage of null values.

<h3> Entity-sets A and B, relationship-set AB </h3>
<h3> Many-to-one mapping </h3>

– A’s participation in AB is total
	`Note : Works for partial too, but may involve null values`

This will generates relation schemas (A, B, AB)
where AB's PK = A's PK

<em> AB relation can be combined with A, The primary key of A will not change, but a new foreign key contraint is created to B</em>

This explains why we model one-to-many relationships with total participation as :
<blockquote>1:N relationships, post the identifier (Primary Key) from the ‘one’ side as an attribute into the ‘many’ side
</blockquote>

<h3> One-to-one mapping </h3>

* We can also combine schemas in this case.

* Could incorporate AB into schema A or, schema B.

* But it is good practice to include it in a schema that has total participation with AB.

* If both A and B are in total participation with AB we can collide all three schemas into one schema.

` NOTE : You cannot combine many-to-many relationships`

All the above details explain why we do what we do when we convert ER diagrams into relational schemas.



