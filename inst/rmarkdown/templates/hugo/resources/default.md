---
author: $if(author)$$author$$endif$
date: $if(date)$$date$$endif$
slug: $if(slug)$$slug$$endif$
draft: True
title: $if(title)$$title$$endif$
categories: Data Science
tags: 
  - R
  - $if(tag1)$$tag1$$endif$
  - $if(tag2)$$tag2$$endif$
image: $if(image)$$image$$endif$
---
$for(header-includes)$
$header-includes$

$endfor$
$for(include-before)$
$include-before$

$endfor$
$if(toc)$
$toc$

$endif$
$body$
$for(include-after)$

$include-after$
$endfor$