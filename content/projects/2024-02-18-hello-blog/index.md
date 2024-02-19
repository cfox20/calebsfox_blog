---
title: Hello Blog
author: 'Caleb Fox'
date: '2024-02-18'
slug: []
categories: []
tags: []
draft: no
---




```r
library("tidyverse")
theme_set(theme_minimal())
theme_update(panel.grid.minor = element_blank(), 
  plot.title = element_text(hjust = 0.5))
```


```r
tibble(x = rnorm(100)) |> 
  ggplot(aes(x)) +
    geom_density()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />

