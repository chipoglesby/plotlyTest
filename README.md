Plotly Test
================

R Markdown
----------

``` r
library(plotly)
library(htmlwidgets)
p <- plot_ly(economics, x = ~date, y = ~unemploy / pop)
p
```
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plot.ly/~chipoglesby/2.embed"></iframe>
