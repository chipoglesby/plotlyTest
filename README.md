Plotly Test
================

R Markdown
----------

``` r
library(plotly)
p <- plot_ly(economics, x = ~date, y = ~unemploy / pop)
p
```
When rendered using `rmarkdown` `plotly` doesn't acutally render the chart to githubpages.

Instead you can use the code below to send data to plotly render it and embed an `iframe`
that will print on a github page.

<iframe width="900" height="800" frameborder="0" scrolling="no" src="https://plot.ly/~chipoglesby/3.embed">
</iframe>
