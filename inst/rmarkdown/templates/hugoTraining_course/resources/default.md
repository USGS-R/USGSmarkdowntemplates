---
date: $if(date)$$date$$endif$
slug: $if(slug)$$slug$$endif$
title: $if(title)$$title$$endif$
draft: True
menu:
  main:
    parent: $if(parent)$$parent$$endif$
    weight: 1
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