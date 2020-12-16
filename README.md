---
output:
  html_document:
    df_print: paged
knit: (function(inputFile, encoding) { rmarkdown::render(
    inputFile,
    encoding = encoding,
    output_dir = "docs",
    output_file='index.html'
  ) })
---

# Baby names

Was originally some help for a student getting these names, but turned into just exploration of things, including the [babynames](https://github.com/hadley/babynames) package.

## Knitted results

- [csv import test](https://utdata.github.io/r-baby-names/01-import-test.html)
- [babynames export](https://utdata.github.io/r-baby-names/01-export-names.html)
