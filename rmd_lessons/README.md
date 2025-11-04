# R markdown instructional material

Last used: 08/2025

Contributors: [Matthew C Chan](https://github.com/matthewcchan), [Mackenzie M Johnson](https://github.com/mmjohn), [Katherine Brower](https://github.com/kteab)

## Contents

### 1. Intro to R 
The first five lessons use the `learnr` [package](https://github.com/rstudio/learnr) to deploy lessons.

#### Getting started

The `learnr` modules require the following dependencies:
```
install.packages("learnr")
install.packages("remotes")
remotes::install_github("rstudio/gradethis")
install.packages("shiny")
```

Open the `.Rmd` file in RStudio and `Run Document`.

#### Lessons

Each lesson contains introduction material and examples designed to be presented as a group. Practice problems and additional challenge problems are followed and may be completed individually or in groups.  


|Day | Directory | Topics Covered | Files |
| :--- |------------|----------------|-------|
| 1 | **01.0_intro_to_R/** | Introduction to R, R basics, RStudio overview | `1.0_intro_to_R.Rmd` |
| 2 | **02.0_vectors/** | Creating and manipulating vectors, vector types | `2.0_vectors.Rmd` |
| 3 | **03.0_functions/** | Using functions, arguments, return values | `3.0_functions.Rmd` |
| 4 | **04.0_vector_operations/** | Comparison operators, logical comparisons, missing data | `4.0_vector_operations.Rmd` |
| 5 | **05.0_review/** | Review of basic R concepts (vectors, functions, operations) | `5.0_review.Rmd` |



### 2. Data Manipulation/Tidyverse

The following lessons are implemented using [R markdown](https://github.com/rstudio/rmarkdown).

#### Lessons 
| Day | Directory | Topics Covered | Files |
| :--- |------------|----------------|-------|
|6 | **06.0_dataframes/** | Exploring dataframes | `6.0_dataframes_worksheet.Rmd`, `6.1_dataframes_group_activity.Rmd`, `6.2_dataframes_exercises.Rmd` |
|7 | **07.0_tidyverse/** | Introduction to the tidyverse, tidying data, `select()` and `filter()` | `7.0_tidyverse_worksheet.Rmd`, `7.0_tidyverse_worksheet_KEY.Rmd`, `7.1_tidyverse_group_activity.Rmd`, `7.2_tidyverse_exercises.Rmd`, `7.2_tidyverse_exercises_KEY.Rmd`,  |
|8 | **08.0_piping/** | The pipe operator (`%>%`), chaining operations | `8.0_piping_worksheet.Rmd`, `8.0_piping_worksheet_KEY.Rmd`, `8.1_piping_group_worksheet.Rmd`, `8.2_piping_exercises.Rmd`, `8.2_piping_exercises_KEY.Rmd`, `clinical.csv` |
|9 | **09.0_data_manipulation/** | Data wrangling with `dplyr`: `mutate()`, `group_by()`, `tally()`, `summarize()`, `count()` | `9.0_data_manipulation_worksheet.Rmd`, `9.0_data_manipulation_worksheet_KEY.Rmd`, `9.1_data_manipulation_exercises.Rmd`, `9.2_data_manipulation_exercises.Rmd`, `9.3_data_manipulation_exercises.Rmd` |
|10 |  | Extra time for practice/Review | 
### 3. Data Visualization

The following lessons are implemented using [R markdown](https://github.com/rstudio/rmarkdown).

#### Lessons 
|Day| Directory | Topics Covered | Files |
|:--- |------------|----------------|-------|
| 11 | **11.0_plots/** | Intro to data visualization with `ggplot2`, plot layers | `11.0_intro_to_plots_lesson.Rmd`, `11.0_intro_to_plots_lesson_KEY.Rmd`, `11.1_intro_to_plots_exercise.Rmd`, `11.1_intro_to_plots_exercise_KEY.Rmd` |
| 12 | **12.0_plots2/** | Advanced plotting: themes, aesthetics, customization | `12.0_plots_2.0_lesson.Rmd`, `12.0_plots_2.0_lesson_KEY.Rmd` |
