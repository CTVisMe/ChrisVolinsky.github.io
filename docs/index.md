---
title: "index.Rmd"
output: 
  html_document:
    keep_md: true
knit: (function(input_file, encoding) {
    out_dir <- 'docs';
    rmarkdown::render(input_file,
      encoding=encoding,
      output_file=file.path(dirname(input_file), out_dir, 'index.html'))})
---

Most basic Rmd file ever



