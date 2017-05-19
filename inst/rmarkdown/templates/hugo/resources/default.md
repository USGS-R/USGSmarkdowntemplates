---
author: $if(author)$$author$$endif$
date: $if(date)$$date$$endif$
slug: $if(slug)$$slug$$endif$
draft: True
title: $if(title)$$title$$endif$
type: post
categories: Data Science
$if(image)$image:$endif$ $if(image)$$image$$endif$
$if(author_twitter)$author_twitter:$endif$ $if(author_twitter)$$author_twitter$$endif$
$if(author_github)$author_github:$endif$ $if(author_github)$$author_github$$endif$
$if(author_gs)$author_gs:$endif$ $if(author_gs)$$author_gs$$endif$
$if(author_researchgate)$author_researchgate:$endif$ $if(author_researchgate)$$author_researchgate$$endif$
$if(author_staff)$author_staff:$endif$ $if(author_staff)$$author_staff$$endif$
$if(author_email)$author_email:$endif$ $if(author_email)$$author_email$$endif$

tags: 
  - R
$if(tag1)$  -$endif$ $if(tag1)$$tag1$$endif$
$if(tag2)$  -$endif$ $if(tag2)$$tag2$$endif$
description: $if(description)$$description$$endif$
keywords:
  - R
$if(tag1)$  -$endif$ $if(tag1)$$tag1$$endif$
$if(tag2)$  -$endif$ $if(tag2)$$tag2$$endif$
$if(keyword1)$  -$endif$ $if(keyword1)$$keyword1$$endif$
$if(keyword2)$  -$endif$ $if(keyword2)$$keyword2$$endif$
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