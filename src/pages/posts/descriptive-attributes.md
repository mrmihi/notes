---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Descriptive Attributes'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

``` Assumption : Participating entity sets are strong entities```  

R (A -> B)  

<h3>Relational schema for R</h3>  

{union of all participaitng entity-sets primary key attributes} [UNION] { descriptive attributes on R}  

( A' PK, B's PK, R's Descriptive attributes )  

Primary key of R depends on the R's mapping cardinality.  

<h3> Binary Relationship-sets </h3>  

<h4> Many - to - many mapping</h4>  

* The union of all entity-set primary keys becomes primary key of R 

R's PK = ( A's PK, B's PK) 

<h4> One - to - many mapping</h4> 

* Primary key of entity-set on "many" side is primary key of relationship  

R's PK = ( PK of the many side ) 

` NOTE : You can combine schemas if you want to here` 
<a href = 'schema-combination.md'>schema-combination</a> 

<h4> One - to - one mapping</h4> 

* Either entity-set's primary key is acceptable 

R's PK = ( A's PK ) OR ( B's PK ) 

` NOTE : You can combine schemas if you want to here` 
<a href = 'schema-combination.md'>schema-combination</a> 

Should enforce candidate key constraint for each! 
	( candidate key constraint -A columns must uniquely idenfiy a row ) 

Don't forget about the foregn key contraints with the participating enitity-sets. 

