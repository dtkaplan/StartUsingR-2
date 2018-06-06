# Starting R

This is an RStudio.cloud project set up by StatPrep Annie to provide templates for other StatPREP instructors using R for their own courses. 

Many R packages are pre-installed in this project. These include:

- tidyverse
- mosaic (which automatically installs mosaicData, mosaicCore, and ggformula)
- mosaicModel
- learnr (which includes shiny, etc)
- knitr

## Connecting to GitHub

1. Go to GitHub and set up a repository with a suitable name for your course.
2. In the Git tab in RStudio, select the "gear" menu and then "shell." This will open up a new tab called "Terminal", next to the console.
3. In the Terminal tab, cut and paste these commands, making sure to provide your own information rather than StatPrep Annie's.

```r
git config --global user.email "StatPrep.Annie@gmail.com"
git config --global user.name "StatPrep Annie"
```

