---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Normalization'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

<h3>First Normal Form</h3>

- Using row order to convey infromation is not permitted
- Mixing data types within the same column is not permitted
- Having a table without a primary is not permitted
- Repeating groups are not permitted

<h3>Second Normal Form </h3>

- Each non-key attribute in the table must be dependent on the entire primary key
+ No partial dependencies

<h3>Third Normal Form </h3>

- Each non-key attribute in the table must be depended on the key, the whole key, and nothing but the key.
+ No transitive dependencies

<h3>Boyce-Codd Normal Form </h3>

- Each attribute in the table must be depend on the key, the whole key, and nothing but the key.
+ Every determinant must be a candidate key

<h3>Fourth Normal Form </h3>

- The only kinds of multivalued dependency allowed in a table are multivalued dependencies on the key.
+ parts of the key should not have multivalued dependency with other parts of the key 

<h3>Fifth Normal Form </h3>

- It must not be possible to describe the table as being the logical result of joinning some other tables together.

<h3>Determinant vs candidate key</h3>

	A primary key or any candidate key is also a determinant while the opposite is not true.
	A determinant can uniquely determine one or more attributes in the row.
	A candidate key can uniquely determine the entire row. 
