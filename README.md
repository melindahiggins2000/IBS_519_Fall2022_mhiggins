# Emory IBS 519 Guest Lectures: Fall 2022
{:.no_toc}

-----

by Melinda Higgins, PhD; [https://melindahiggins.netlify.app/](https://melindahiggins.netlify.app/)

-----

* TOC 1
{:toc}

# Week 1 Lecture 02: Intro to R, RStudio and Rmarkdown

Today's class will cover:

* Explore RStudio environment
    - command line
    - R scripts
    - packages
    - getting help 
* R markdown intro (brief)
* Importing & viewing data
    - [abalone dataset](https://archive.ics.uci.edu/ml/datasets/abalone)
    - `str()`, `dim()`, `head()`, `tail()` functions
* Data types - classes of variables
    - strings
    - integers
    - numeric
    - logical
    - factors (brief intro)

## Materials

* RStudio Cloud Project "IBS_519_wk1_lecture02_mhiggins"
    - three R scripts
    - and simple Rmarkdown report to get started
    - stored on [Github](https://github.com/melindahiggins2000/IBS_519_wk1_lecture02_mhiggins)
* Optional: [Introduction to R Objects](https://melindahiggins2000.github.io/N741_Spring2021_lesson04_dataWranglingDplyr/N741_IntroductionToRObjects_mkh.html#1)
* Optional: [R Objects - Brief Overview of Factors](https://melindahiggins2000.github.io/N741_Spring2021_lesson04_dataWranglingDplyr/N741_RObjectsFactors_mkh.html#1)
* Optional: [Intro to ggplot2 (i.e. week 2)](https://melindahiggins2000.github.io/N741_Spring2021_lesson04_dataWranglingDplyr/N741_IntroductionToGgplot2_mkh.html#1)
* Optional: 
    - [Intro to Data Wrangling with dplyr (i.e. week 3)](https://melindahiggins2000.github.io/N741_Spring2021_lesson04_dataWranglingDplyr/N741_IntroductionToDataWrangling_mkh.html#1)
    - [Another Intro to dplyr](https://melindahiggins2000.github.io/CDC_Rworkshop_April2022/CDCRworkshop_April2022_Module04.html#1)

# Week 3 Lecture 06: Data Exploration and Wrangling (with dplyr)

Today's class will cover:

* Data exploration
    - numerical exploration
        - `summary()` function
        - `describe()` function from [`Hmisc` package](https://hbiostat.org/R/Hmisc/)
        - `describe()` function from [`pysch` package](https://cran.r-project.org/web/packages/psych/index.html)
    - graphical exploration
        - histograms
        - scatterplots
        - learn more at:
            - [R Graphics Cookbook](R Graphics Cookbook, 2nd edition)
            - [Cookbook for R, graphics codes for book](http://www.cookbook-r.com/Graphs/)
            - [R Graph Gallery](https://r-graph-gallery.com/)
* more with the `abalone` dataset
* Tidyverse - [`dyplr` package](https://dplyr.tidyverse.org/index.html)
    - glimpse
    - select
    - filter (explore and clean)
    - arrange
    - mutate (making new variables)
    - rename
    - summarise
    - group_by
    
## Materials

* Slides
* RStudio Cloud Project - in class exercises
* RStudio Cloud Project - Homework 3

# Week 4 Lecture 08: Reproducible Research and RMarkdown

Today's class will cover:

* Learn about reproducible research workflows
* Make your life easier with [Rmarkdown](https://rmarkdown.rstudio.com/)
    - [Rmarkdown Output Options](https://rmarkdown.rstudio.com/gallery.html)
    - make DOCX and HTML reports (PDF optional)
    - turn last week's in-class exercise code and turn it into a report
* Writing a step-by-step analysis report 
    - [`knitr` package](https://cran.r-project.org/web/packages/knitr/index.html)
    - [`printr` package](https://cran.r-project.org/web/packages/printr/)

## Materials

* Slides
* RStudio Cloud Project - in class exercises

# R/RStudio Helpful Resources

* [Download: R from CRAN](https://cran.r-project.org/)
    - This is where you can download the R language software for FREE for your own computer.
    - Choose your operating system (Mac OS or Windows or Linux/Unix)
    - NOTE: For Windows, you should also download and install [Rtools](https://cran.r-project.org/bin/windows/) - this is technically optional, but is useful to have. Make sure to download the one for your R version.
    
* [Download: RStudio IDE Desktop](https://www.rstudio.com/products/rstudio/download/#download)
    - Note: Windows is listed at the top - just scroll down to see the installer for the Mac OS as well. There are also installers for the versions of Linux/Unix.

* [RStudio Education](https://education.rstudio.com/)
* [RStudio Cloud Tutorials](https://rstudio.cloud/learn/primers)
* [** Quick-R **](https://www.statmethods.net/)
* [Rmarkdown Tutorial](https://rmarkdown.rstudio.com/lesson-1.html)
* [tidyverse](https://www.tidyverse.org/)

* [Datacamp](https://www.datacamp.com/)
* [R for SAS Users - My Datacamp Course](https://www.datacamp.com/courses/r-for-sas-users)
* [Coursera](https://www.coursera.org/)
* [Reproducible Templates for Analysis and Dissemination - My Coursera Course](https://www.coursera.org/learn/reproducible-templates-analysis)
* [Emory N741](https://melindahiggins2000.github.io/N741bigdata/)
* [Emory N736](https://melindahiggins2000.github.io/N736/)
* [Book: Statistical Inference via Data Science](https://moderndive.com/)
* [Book: The Epidemiologist R Handbook](https://epirhandbook.com/en/index.html)
* [Book/Course: Stat 545](https://stat545.com/)

