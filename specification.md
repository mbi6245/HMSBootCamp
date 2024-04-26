# Data Analysis - Assignment Specification

The purpose of this assignment is to give you hands-on experience programming in R and answering statistics questions you'll commonly see in your courses at the UW. The primary purpose of this assignment is to familiarize you with best practices according to UW STAT/BIOST faculty.

- For beginners: you'll get to dip your toes into a UW STAT/BIOST style assignment before your first day of class
- For those with experience: you'll get practice with how you should phrase interpretations of statistical concepts in your courses

Everyone will come out with hands-on experience with statistics/R programming, and be able to put what they learned on display publicly (or privately!) using GitHub.

# Overview

It's best to split the work up into multiple days. If you just went through the setup guide, take a break and come back tomorrow!

If you're already proficient with GitHub and R programming, mainly focus on the content regarding how to write statistical analyses, contained in the slides for Day 4.

## ChatGPT

Use of ChatGPT is permitted, but not required for the completion of this assignment; it was designed with ChatGPT in mind. The vast majority of BIOST courses at UW follow similar policies, and focus on statistical interpretations instead


## Suggested Workflow

- Each day you plan to work on this project, click one of the hyperlinks "Day X" below to take you to a slidedeck that will provide basic instruction on various parts of the assignment
- Read through the slidedeck (feel free to experiment while doing so!) and once you hit a slide with red title text ("Question X"), go to the assignment
- Do the corresponding question on the assignment and repeat!

## Schedule

<!-- lets try to stay away from base r commands for now, mention ChatGPT is ok for code, but not for analysis -->

1. [Day 1:](https://docs.google.com/presentation/d/1ZbkhEe2oIbKtkKZFMg64hnVnUX3RPu_eSJ1dRR2xslY/edit?usp=sharing) Basic git commands and Rstudio setup
1. [Day 2:](https://docs.google.com/presentation/d/1z-T-SRFQyL5lYsLgSDSbgguDmFFsyfDfnjsd_r4dUQY/edit?usp=sharing) R Basics and Data Wrangling

    variable assignment in R, ?function to view documentation, borrow data wrangling from Peng (import csv, NA strings, checking for NA, filter rows, rearrange rows, new col in df, save df as csv, bind_rows, group_split), but put it in the form of a question
1. [Day 3:](https://docs.google.com/presentation/d/1CbUCN9RhhKkkofRPcjBPxe6D2AnutVX9RoX4jvBKadU/edit?usp=sharing) Descriptive Statistics and Plotting
1. [Day 4:](https://docs.google.com/presentation/d/1ymt9pRfz-BL_83jhW0XJGVtkFKZB_TK1yr8xqxwRUXY/edit?usp=sharing) Regression in R

    take format from BIOST514 hw4 q4 and combine with BIOST515 hw1 q2 for sure, maybe q4 and 5, using the bodyfat dataset

# Assignment

In this assignment, you'll be analyzing some data from the the fev dataset, which is a commonly used dataset about lung function in children who are smokers and non-smokers.

1. Question 1: edit the **README.md** file in this repository to be a brief description of the data analysis you hope to do in this assignment
1. Question 2: install the `tidyverse` and `regress` packages within RStudio