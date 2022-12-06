---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Nested Query Operators'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---
<hr>

value `IN` [ L1 , L2 , ... , Ln ]
\
\
    ( value = L1 ) OR ( value = L2 ) OR ... ( value = Ln )
\
\
value [ operator ] `ANY` [ L1 , L2 , ... , Ln ]
\
\
    ( value [ operator ] L1 ) OR (value [ operator ] L2 ) OR ... (value [ operator ] Ln )
\

<blockquote> Notice that '= ANY' does the same function as 'IN' </blockquote> 

\
value [ operator ] `ALL` [ L1 , L2 , ... , Ln ]
\
\
    ( value [ operator ] L1 ) AND ( value [ operator ] L2 ) AND ... ( value [ operator ] Ln )
\