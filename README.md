---
title: "Week 2 Assignment"
output:
  html_document:
    keep_md: yes
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(leaflet)
```

#April 23, 2018
```{r, echo = FALSE}
my_map <- leaflet() %>% 
  leaflet::addTiles() %>% 
  addMarkers(lat = 42.319096,lng = -83.682783,label = "Come check out the bison and eat pizza!" )
my_map

```
