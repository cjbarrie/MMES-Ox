[![Build Status](https://travis-ci.com/rstudio/bookdown-demo.svg?branch=master)](https://travis-ci.com/rstudio/bookdown-demo)

This is a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

NOTE TO SELF:

Workflow:

- Open MMES-Ox.Rproj and update bookdown files with bookdown::render_book() and push to Github.
- Close MMES-Ox.Rproj
- Open MMES-2021.Rproj, serve bookdown with bookdown::serve_book()
- Check all updated correctly
- Publish book to bookdown URL with bookdown::publish_book()
- If requested for account details etc., specify options as: bookdown::publish_book(name = "MMES-2021", account = "chrisjbarrie", render = "server")
