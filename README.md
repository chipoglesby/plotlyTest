Plotly Test
================

R Markdown
----------

``` r
library(plotly)
p <- plot_ly(economics, x = ~date, y = ~unemploy / pop)
p
```

