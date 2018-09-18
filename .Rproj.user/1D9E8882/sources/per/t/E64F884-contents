#!/bin/sh

Rscript -e "bookdown::render_book('./paper/index.Rmd', 'bookdown::gitbook')"
Rscript -e "bookdown::render_book('./paper/index.Rmd', 'bookdown::pdf_book')"
Rscript -e "bookdown::render_book('./paper/index.Rmd', 'bookdown::epub_book')"

