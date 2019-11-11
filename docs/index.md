--- 
title: "R Markdown for Scientists"
author: "Nicholas Tierney"
date: "2019-11-11"
knit: "bookdown::render_book"
description: "A book created for a 3 hour workshop on R Markdown"
documentclass: krantz
site: bookdown::bookdown_site
bibliography: [book.bib, packages.bib]
biblio-style: apalike
colorlinks: yes
fontsize: 12pt
monofont: "Source Code Pro"
monofontoptions: "Scale=0.7"
link-citations: yes
url: 'https\://openplantpathology.github.io/rmd4sci-melbourne/'
---

# About this {-}

<img style="float:right" src="figs/OPP logo hex.png"> This is a book on R Markdown, aimed for scientists. It was initially developed as a 3 hour workshop, but is now developed into a resource that will grow and change over time as a **living book**.

This book aims to teach the following:

- Getting started with your own R Markdown document
- Improve workflow:
  - With RStudio projects
  - Using keyboard shortcuts
- Export your R Markdown document to PDF, HTML, and Microsoft Word
- Better manage figures and tables
    - Reference figures and tables in text so that they dynamically update
    - Create captions for figures and tables
    - Change the size and type of figures
    - Save the figures to disk when creating an R Markdown document
- Work with equations
    - inline and display
    - caption equations
    - reference equations
- Manage bibliographies
  - Cite articles in text
  - generate bibliographies
  - Change bibliography styles
- Debug and handle common errors with R Markdown
- Next steps in working with rmarkdown - how to extend yourself to other R Markdown formats
    
## Why write this as a book?

There are many great books on R Markdown and it's various features, such as ["R Markdown: The definitive guide"](https://bookdown.org/yihui/rmarkdown/), ["bookdown: Authoring Books and Technical Documents with R Markdown"](https://bookdown.org/yihui/bookdown/), and ["Dynamic Documents with R and knitr, Second edition"](https://www.crcpress.com/Dynamic-Documents-with-R-and-knitr/Xie/p/book/9781498716963), and Yihui Xie's thesis, ["Dynamic Graphics and Reporting for Statistics"](https://lib.dr.iastate.edu/etd/13518/).

> So why write a book?

Good question. The answer is that writing this as a book provides a way for me to structure the content in the form of a workshop, in a way suitable for learning in a few hours. 

## How to use this book

This book was written to provide course materials for a 3 hour course on R Markdown.

We worked through the following sections in the book in 3 hours:

- [Why use R Markdown](why-rmd)
- [Installation](installation)
- [What is RStudio?](rstudio)
- [Suggested Workflow and Hygiene](workflow)
- [How to use R Markdown](using-rmd)
- [Using R Markdown with pdf, html, and Word](pdf-html-word)
- [What are Some Useful Keyboard Shortcuts](keyboard-shortcuts)
- [Adding Captions to Tables and Figures](figures-tables-captions)
- [Changing Figures](changing-figures)
- [Adding mathematics](math)
- [Citing Figures and Tables](cite-fig-tab-sec)
- [Changing Citations and styles](citations-and-styles)

With the remaining sections being used as extra material, or have since been written after the course:

- [Fixing some Common Problems in R Markdown](common-problems)
- [What are some Alternative Outputs of rmarkdown?](alternative-outputs-and-exts)
- [Where to Go Next?](next-steps)
- [Suggested References](references)

Course materials can be downloaded by using the following command from the `usethis` package:


```r
usethis::use_course("bit.ly/rmd4sci-materials")
```


## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
