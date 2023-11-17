
<!-- README.md is generated from README.qmd. Please edit that file -->

# R Project Management

<!-- badges: start -->
<!-- badges: end -->

This repo contains materials and resources for a 1-day course in project
management in R. It is a quarto website, and as such adhered to basic
[quarto conventions](https://quarto.org/docs/websites/).

- `slides` contains the slides for the course
- `sections` contains the child quarto sections reused in the materials
- `_quarto.yaml` contains the quarto configuration for the course
- `index.qmd` contains the course homepage

The repo uses [renv](https://rstudio.github.io/renv/) to manage package
dependencies. To install the packages used in this course, run
`renv::restore()` from the project root.

As researchers grow in their skills, eventually the infrastructure
surrounding the analysis will become an important catalyst for the
reproducibility and longevity of analysis artefacts. Researchers are
capable of creating complex and impressive projects, but it is unlikely
to have benefited from any formal training or mentorship related to
topics regarding project management. As a result of this,
reproducibility and longevity of projects are likely to suffer. Learning
aspects of project management is a vital, but rarely taught, skill when
working on a project. While project management has some general
guidelines that traverse fields, there are specific aspects to think
about when working R, given R’s idiosyncrasies.

<div class="callout-tip">

## Aims

- Understand what a working environment is and how R deals with them

- Successfully implement a project-oriented workflow

- Understand best-practice naming of files

- Know how to practice safe paths from R

- Understand basics of R package management

</div>

## Schedule [^1]

|                                           |            |
|-------------------------------------------|-----------:|
| Saving source and blank slates            |     1 hour |
| Project-oriented workflow                 |     1 hour |
| How to name files & practicing safe paths |     1 hour |
| Lunch break                               | 30 minutes |
| R package management                      |  1.5 hours |

## Preparations

You might already have R and RStudio installed on your system. We highly
recommend updating both of them to the latest version before the
workshop, to ensure you can follow along all the exercises.

<div class="callout-note">

### Install summary

- install/update [R](https://cran.rstudio.com/)

- install/update [RStudio](https://posit.co/download/rstudio-desktop/)

</div>

A new version of RStudio and R is recommended. Even if you have R and
RStudio installed on your system, you should update all them before the
workshop if you installed them longer than 2 months ago.

### R packages

In addition to R and RStudio, a series of R packages will also be needed
to complete the workshop tasks.

``` r
# Run in R
install.packages(c(
  "remotes",      # installing packages from GitHub
  "rmarkdown",    # rendering reports
  "fs",           # file system operations
  "here",         # navigating paths
  "usethis",      # for course materials
  "tidyverse"     # data-wrangling
))
```

# Resources

- Workshop website: <https://www.capro.dev/workshop_rproj/>
- [What They Forgot to Teach you about R](https://rstats.wtf/)
- [Happy Git With R book](https://happygitwithr.com)

[^1]: This course relies heavily on materials from [What They Forgot to
    Teach you about R](https://rstats.wtf/), which is an excellent
    resource to dig deeper into to improve the way you work in R.
