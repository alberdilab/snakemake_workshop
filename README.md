# Snakemake workshop

Repository of the Snakemake workshop

The rendered version of this repository can be found in:
https://alberdilab.github.io/snakemake_workshop

## Render webook

The webbook has been rendered using the following script:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```

