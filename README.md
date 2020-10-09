# Christian Reitan's Curriculum Vitae

Academic CV built using R. Academic references retrieved from [Google Scholar](https://scholar.google.com/citations?user=GqZm90IAAAAJ&hl=en) each week. I built it using [Sam Abbotts](https://github.com/seabbs/cv) CV, mostly for the looks though. It is, however, a nice and simple CV, feel free to use it as a template. 

## CV
Can be seen [´{here}´](https://github.com/drwernicke/cv/raw/master/cv/cv.pdf).

## Structure

- `cv/cv.Rmd`: CV structure implemented as an [`{rmarkdown}`](https://rmarkdown.rstudio.com) document.
- `scripts/install.R`: Installs/loads all `R` dependencies using the [`{pacman}`](https://github.com/trinker/pacman) :package:.

## Tools

- The [`{vitae}`](https://docs.ropensci.org/vitae/) :package: is used to provide a CV template.
- [`{tidyverse}`](https://www.tidyverse.org) :tool: are used for data read in and manipulation.
- [`{here}`](https://here.r-lib.org) :package: for path management.
- [`{scholar}`](https://github.com/jkeirstead/scholar) :package: is used to pull papers from Google Scholar.
- [`{tinytex}`](https://github.com/yihui/tinytex) :package: to manage LaTex installation and additional packages.

