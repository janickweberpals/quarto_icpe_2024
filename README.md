# About

This repository contains all materials for the introduction to literate programming and reporting using quarto.

Slides can be accessed at: <https://janickweberpals.github.io/quarto_icpe_2024/index.html#/title-slide>

## Dependencies

This is a quarto project and dependencies are managed through the `renv` package. All packages and their versions can be viewed in the lockfile `renv.lock`. All required packages and the appropriate versions can be installed by running the following command:

```
renv::restore()
```

The dependencies are managed through Posit's repository package manager (RSPM) version for the MacOS distributions. If you use a different operating system, please head over to the RSPM setup website and follow these steps:

1.  Go to the [RSPM setup website](https://packagemanager.posit.co/client/#/repos/cran/setup?distribution=redhat-9)

2.  Choose the operating system (if Linux, also choose the Linux distribution)

3.  Go to **`Repository URL:`** and copy-paste the URL to the options statement in the `.Rprofile` file

    *options(repos = c(REPO_NAME = "URL"))*

## Reproducibility

Follow these steps in RStudio to reproduce the presentation:

1.  Install all necessary dependencies (see above)
2.  Run all scripts via `quarto render` or in RStudio `Build > Render Book` (make sure quarto is installed)
