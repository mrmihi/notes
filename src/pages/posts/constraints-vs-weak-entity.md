---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Participating constraint'
pubDate: 2022-12-04
description: ''
author: 'Dinal'
tags: ["ISDM","DMS","Y1S2","Y2S1"]
---

<hr/>

Participating constraint specifies whether the existence of an entity depends on its being related to another entity via the relationship type.

## Weak Entity

Should have these two attributes.

1. The entity is existence-dependent on another entity. <br>
2. The entity cannot be uniquely identified by its own attributes.

How will those attributes convert into a data model ?

1. The entity will have a total participation constraint with a strong entity. <br>
2. The entity gets at least part of its primary key from the strong entity.
