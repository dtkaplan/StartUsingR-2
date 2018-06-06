# Starting R

This is an RStudio.cloud project set up by StatPrep Annie to provide templates for other StatPREP instructors using R for their own courses. 

Many R packages are pre-installed in this project. These include:

- tidyverse
- mosaic (which automatically installs mosaicData, mosaicCore, and ggformula)
- mosaicModel
- learnr (which includes shiny, etc)
- knitr

## Copying StatPrep Annie's StartUsingR project

1. Using your browser, login to your account on `rstudio.cloud`. The main page for your "workspace" will be displayed.
2. Open a new tab in the browser. Cut and paste exactly this URL into that new tab.
    `https://rstudio.cloud/project/40418`
    Annie's template will be copied into your workspace. It will open with a red "Temporary" in the top line.
3. Press "Save permanent copy" so that you have your own, fully independent copy of Annie's StartUsingR project.

## Connecting to GitHub

Your task now is to connect your own copy of the StartUsingR project to GitHub.

1. Go to GitHub and set up a repository with a suitable name for your course, for instance, `Stat101`.
2. In the Git tab in RStudio, select the "gear" menu and then "shell." This will open up a new tab called "Terminal", next to the console.
3. In the Terminal tab, cut and paste these commands, making sure to provide your own information rather than StatPrep Annie's. Press enter. You're going to be using the terminal tab later, as well.

```r
git config --global user.email "StatPrep.Annie@gmail.com"
git config --global user.name "StatPrep Annie"
```
4. Give the command, in the terminal tab, that will instruct RStudio to refer to your GitHub repository. The command will look like the following, but **you must** change `USERNAME` to be your own GitHub username, and change `REPOSITORY` to be your own repository, set up in Step (1) of this section.
```
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```
