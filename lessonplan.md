<!-- 
This file by Martin Monkman is licensed under a Creative Commons Attribution 4.0 International License. 
It is adapted from original work by:
- Charlotte Wickham; https://github.com/cwickham/data-science-in-tidyverse 
- RStudio; https://github.com/rstudio/master-the-tidyverse
- Data Carpentries; https://datacarpentry.org/r-socialsci/ 
-->

# CDSC103: Lesson Plan

### _2020-01-11_

latest revision: 2020-01-01

The course outline for Developing a Data Analysis Toolbox, SFU CDSC103


***

**_subject to change_**



## Objectives

> The important thing is that you solve the problem that you’re working on, not write the most concise and elegant code (although that’s definitely something you want to strive towards!)
> - Grolemund & Wickham, _R for Data Science_


At the end of this lesson, learners will be able to:

1. Install and navigate R, RStudio, and tidyverse packages;

2. Import data from a variety of sources, and write output files;

3. Understand and apply data manipulation and modeling methods; 

4. Build and customize complex plots and reproducible reports from data in a data frame.



***

## Activities

| Block      | Time           | Topics  | &#8212; |
|---         |:---            |:---     |:---:  |
|1a          | 9:00 to 9:30   | Welcome and warm-up  | &#8212; |
|1b <br> 1c  | 9:30 to 10:30  | Why code? Why R? <br> Introduction to R and RStudio | &#8212; |
|&#8212;     | 10:30 to 10:45 | _break_ | &#8212; |
|2a <br> 2b  | 10:45 to 12:00 | Data manipulation <br> Importing data  | &#8212; |
|&#8212;     | 12:00 to 1:00  | _lunch_ | &#8212; |
|3a <br> 3b  | 1:00 to 2:30   | Data manipulation (continued) <br> Modeling | &#8212; |
|3c          | 2:30 to 2:45   | Exporting data | &#8212; |
|&#8212;     | 2:45 to 3:00   | _break_ | &#8212; |
|4a          | 3:00 to 4:30   | Communicating: Plotting & Reporting | &#8212; |
|4b          | 4:30 to 5:00   | Wrap up | &#8212; |



### 1a. Welcome and warm-up

Format: participation and instructor lecture w/ slides

Time allocation: 30 minutes (9:00 to 9:30)



### 1b. Why Code? Why R?

Format: participation and instructor lecture w/ slides

Time allocation: 15 minutes (9:30 to 9:45)


### 1c. An introduction to R, RStudio, RStudio Cloud, and R Markdown

Format: learner (instructor guided), using RStudio Cloud

Time allocation: 45 minutes (9:45 to 10:30)



## BREAK

Time allocation: 15 minutes (10:30 to 10:45)

***

### 2a. Data manipulation

Format: learner (instructor guided)

Time allocation: 45 minutes (10:45 to 11:30)



### 2b. Importing data

Format: learner (instructor guided)

Time allocation: 30 minutes (11:30 to 12:00)







***

## LUNCH

Time allocation: 60 minutes (12:00 to 1:00)

***

### 3a. Data manipulation (part 2)

Format: instructor, lecture w/slides

Time allocation: 15 minutes (1:00 to 1:15)


Format: learner (instructor guided)

Time allocation: 45 minutes (1:15 to 2:00)



### 3b. Modeling

Format: learner (instructor guided)

Time allocation: 30 minutes (2:00 to 2:30)


### 3c. Exporting data

Format: learner (instructor guided)

Time allocation: 15 minutes (2:30 to 2:45)

***

## BREAK

Time allocation: 15 minutes (2:45 to 3:00)


***

## 4a. Communicating: plotting and reporting

Format: learner (instructor guided)

Time allocation: 90 minutes (3:00 to 4:30)



## 4b. Wrap up

Time allocation: 30 minutes (4:30 to 5:00)





***

## Packages: resources

### R Markdown

[R Markdown reference at RStudio](https://rmarkdown.rstudio.com/docs/)

[R Markdown cheat sheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf) (PDF file)


### The tidyverse:

[tidyverse.org](https://www.tidyverse.org/)


#### {ggplot2} .

[{ggplot2} reference at tidyverse.org](https://ggplot2.tidyverse.org/) -- "a system for declaratively creating graphics, based on _The Grammar of Graphics_"

[Data Visualization with {ggplot2} cheat sheet](https://rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf) (PDF file)


#### {dplyr} .

[{dplyr} reference at tidyverse.org](https://dplyr.tidyverse.org/) -- "a grammar of data manipulation"

[Data Transformation Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf) (PDF file)

[Data wrangling with {dplyr} and {tidyr} cheat sheet](https://rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf) -- note: has not yet been updated to the latest {tidyr} syntax (i.e. no `pivot_longer()` and `pivot_wider()`)


#### {readr} .

[{readr} reference at tidyverse.org](https://readr.tidyverse.org/) -- "a fast and friendly way to read rectangular data (like csv, tsv, and fwf)"



#### {readxl} .

[{readxl} reference at tidyverse.org](https://readxl.tidyverse.org/) -- "makes it easy to get data out of Excel and into R"



#### {tidyr} .

[{tidyr} reference at tidyverse.org](https://tidyr.tidyverse.org/) -- "help you create tidy data"

[Data wrangling with {dplyr} and {tidyr} cheat sheet](https://rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf) -- note: has not yet been updated to the latest {tidyr} syntax (i.e. no `pivot_longer()` and `pivot_wider()`)


### Utilities

#### {janitor}

[{janitor} reference](http://sfirke.github.io/janitor/) -- "simple functions for examining and cleaning dirty data"


***

## Readings & Reference Materials


### From _R4DS_

Garrett Grolemund and Hadley Wickham, [R for Data Science](https://r4ds.had.co.nz/)

* [4. Workflow: basics](https://r4ds.had.co.nz/workflow-basics.html)

* [5. Data Transformation](https://r4ds.had.co.nz/transform.html)

* [6. Workflow: scripts](https://r4ds.had.co.nz/workflow-scripts.html)

* [27. R Markdown](https://r4ds.had.co.nz/r-markdown.html)

* [12. Tidy data](https://r4ds.had.co.nz/tidy-data.html)


### Digging deeper


#### Opinionated analysis development / reproducible analysis

Hilary Parker, 2017-08-31, [Opinionated analysis development](https://peerj.com/preprints/3210/), PeerJ Preprints 5:e3210v1 https://doi.org/10.7287/peerj.preprints.3210v1

[The reproducible workflow](https://remi-daigle.github.io/2017-CHONe-Data/cleaning.nb.html) -- from Data Management Workshop à la CHONe

Munafò, M., Nosek, B., Bishop, D. et al. [A manifesto for reproducible science](https://www.nature.com/articles/s41562-016-0021). Nat Hum Behav 1, 0021 (2017) doi:10.1038/s41562-016-0021


#### Why R?

Nathaniel D. Phillips, [YaRrr! The Pirate’s Guide to R](https://bookdown.org/ndphillips/YaRrr/) 

- [Chapter 1.3, "Why is R so great?"](https://bookdown.org/ndphillips/YaRrr/why-is-r-so-great.html)

- [Chapter 2, "Getting Started"](https://bookdown.org/ndphillips/YaRrr/started.html) provides a good summary of R, RStudio, and packages

"History and Overview of R", Chapter 2 in Roger Peng, 2019-12-22, [_R Programming for Data Science_](https://bookdown.org/rdpeng/rprogdatascience/history-and-overview-of-r.html)

Lucy D'Agostino McGowan, 2017-07-28, [R release names](https://livefreeordichotomize.com/2017/09/28/r-release-names/)

- [an up-to-date list](https://bookdown.org/martin_monkman/DataScienceResources_book/using-r.html#r-release-names)


#### Naming things

Jenny Bryan, ["How to name files"](https://speakerdeck.com/jennybc/how-to-name-files)

* https://twitter.com/JennyBryan/status/807805087544328192?s=20


#### R Markdown

[Introduction to literate programming in R](https://remi-daigle.github.io/2017-CHONe-Data/Rmarkdown.nb.html) -- from Data Management Workshop à la CHONe


#### Tidy data

Hadley Wickham. ["Tidy data"](https://www.jstatsoft.org/article/view/v059i10), _The Journal of Statistical Software_, vol. 59, 2014.

Karl Broman and Kara Woo, ["Data organization in spreadsheets"](https://doi.org/10.1080/00031305.2017.1375989), _The American Statistician_ 72 (1): 2–10.

[Data Organization in Spreadsheets for Social Scientists: Formatting problems](https://datacarpentry.org/spreadsheets-socialsci/02-common-mistakes/index.html) -- DataCarpentry lesson

[Data organization with spreadsheets](https://remi-daigle.github.io/2017-CHONe-Data/organization.nb.html) -- from Data Management Workshop à la CHONe





-30-
