# RJsandboxweb
Web version of R Journal article submission

https://cmtso.github.io/RJsandboxweb/sandbox

Under revision in the R Journal: [![RJournal paper](https://img.shields.io/badge/DOI%20(R%20Journal)-https%3A%2F%2F10.32614%2FRJ--2021--097-blue)](https://doi.org/10.32614/RJ-2021-097)


You can write R journal articles with R markdown to produce both the LaTex and web version. See *sandbox.Rmd*. 
- To pdf: `rticles::rjournal_article`, which will generate *sandbox.tex* too
- To web article: `rjtools::rjournal_web_article `

Note: the abstract of the web version is pulling to the right for some reason.
