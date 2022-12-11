---
title: "Hello World Markdown"
author: "David Crone"
date: "2022-12-11"
output: 
  html_document:
    keep_md: TRUE
---





```r
my_data <- data.frame(x = 1:3, y = 4:6)

sum(my_data$x, my_data$y)
```

```
## [1] 21
```

```r
plot(my_data$x, my_data$y)
```

![](hello_world_md_files/figure-html/unnamed-chunk-2-1.png)<!-- -->
