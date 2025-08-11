# Snakemake workshop

Repository of the Snakemake workshop

## Render webook

The webbook has been rendered using the following script:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```

