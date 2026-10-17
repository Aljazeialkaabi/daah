---
layout: single
title: "Introduction to R and RStudio"
permalink: /extra-credit-1/
---


## Introduction

On September 25, 2026, I attended an online Introduction to R and RStudio workshop through Zoom from 10 PM to 12 AM UAE time. The workshop was led by Rophence Ojiambo and introduced us to R, a programming language used for statistical analysis and working with data.

I was interested in attending because we have already been working with datasets and computational tools in our class. Although I had some experience using Posit Cloud for our Science Fiction Explorer assignment, I wanted to understand more about how R actually works and what we can do with it beyond the activities we have already completed in class.

The workshop covered quite a lot, starting with the RStudio interface and basic commands before moving into vectors, data frames, missing data, piping, and dataset manipulation. Some concepts were familiar from my other programming experiences, while others were completely new to me.

## Getting Familiar with RStudio

The workshop began with an introduction to the RStudio interface. One of the first things we learned was that RStudio is divided into four main panes each serving a different purpose.

The Source pane is where we write and save our code, while the Console is where R executes commands and displays the results. The Environment pane shows the objects and variables R currently has stored in its memory. Finally, the Files, Plots, Packages, and Help pane allows us to navigate files, view visualizations, manage packages, and access documentation.

I found the Environment pane interesting because it allows us to see what R remembers from the commands we have executed. This also helped me understand why certain errors happen when we try to reference an object that has not been created.

We also learned about RStudio Projects, which help organize files and code within a specific working directory. Rather than constantly specifying where datasets are located, a project can make it easier to work with files in the same folder. I thought this was useful because keeping track of different files and their locations is something I have struggled with in other coding projects even in other classes such as Comms Lab.

![The four main panes of the RStudio interface]({{ '/assets/images/extra-credit/extracred-figure1.png' | relative_url }})

*Figure 1: The RStudio interface during the [Introduction to R workshop](https://guides.nyu.edu/ds_class_descriptions/Introduction-to-R). Screenshot taken by me during the Zoom session, September 25, 2026.*

## Working with Data

After getting familiar with the interface, we started learning how to actually work with data in R. We began with vectors, which are used to store values of the same data type. We learned how to create vectors using the `c()` function and perform different calculations using functions like `mean()`, `sum()`, and `length()`. One thing the instructor emphasized was the importance of writing meaningful comments in our code. I thought this was a good reminder because sometimes when I code, I understand what I am doing at that moment, but when I come back to it later, I forget why I wrote certain things.

We then moved on to data frames, which allow us to organize information into rows and columns. We looked at how to create a data frame and reference specific columns using square brackets or the dollar sign. I found this part easier to follow because I could actually see how the information was being organized into a table. We also discussed missing data, represented by `NA` in R, and how important it is to account for missing values when analyzing datasets. This was something I hadn't really thought much about before, but it made me realize that even missing information can affect the results of an analysis.

![A data frame created in RStudio]({{ '/assets/images/extra-credit/extracred-figure2.png' | relative_url }})

*Figure 2: A data frame created during the [Introduction to R workshop](https://guides.nyu.edu/ds_class_descriptions/Introduction-to-R), showing numerical values and state abbreviations. Screenshot taken by me during the Zoom session, September 25, 2026.*

## Introduction to Piping and Dataset Manipulation

The second half of the workshop focused on piping, which allows us to connect multiple operations together rather than writing everything separately. We learned about two types of pipes, the magrittr pipe `%>%` and the native pipe `|>`, and how they can make code easier to read.

One thing I particularly liked was the morning routine analogy the instructor used to explain piping. She compared it to doing a series of activities in order, where one step leads to the next. I felt like this made the concept much easier to understand because instead of thinking about it as another complicated symbol in programming, I could imagine it as a sequence of actions.

We also learned how to manipulate datasets by sorting information and changing how variables are categorized. For example, using `arrange(Age)` would sort a dataset by age in ascending order, while `arrange(desc(Age))` would sort it in descending order. I thought it was interesting how a few lines of code could change the way we view and organize a dataset.

## Connecting the Workshop to Our Class

Before attending the workshop, I was mostly following the code provided to us in class and changing certain values to explore different results. However, the workshop helped me better understand what some of the commands actually do and how R works behind the scenes.

For example, in class we have been using Posit Cloud to explore datasets, analyze word frequencies, and create visualizations. During the workshop, learning about vectors, data frames, and different functions helped me understand how data is stored and manipulated before we can analyze it. I also found it interesting that the RStudio interface looked familiar because of our work on Posit Cloud, so I wasn't starting completely from scratch.

I think the workshop helped connect what we have been doing in class to the actual programming behind it. I now have a better understanding of how different commands work together and why organizing data properly is important.

## Final Reflection and Future Uses

Overall, I found the workshop useful because it helped me understand RStudio beyond just using it for a class assignment. Some parts were confusing at first, especially when we started introducing new functions and symbols, but I liked how the instructor explained things through examples instead of just showing us code.

As an Interactive Media major at NYUAD, I think what I learned could be useful in future classes, especially if I work on projects involving data visualization or interactive experiences. I could also imagine using R for research or even a future capstone project if I decide to create something involving real datasets. I don't think I fully understand everything about R yet, but the workshop definitely helped me become more familiar with it and showed me how useful it can be beyond the classroom.

## Additional Learning Resources

The following resources were shared during the workshop or can help beginners learn more about R and RStudio:

- [NYU Libraries — Introduction to R](https://guides.nyu.edu/ds_class_descriptions/Introduction-to-R): Information about the introductory R workshop.
- [NYU Data Services — Supported Software](https://guides.nyu.edu/dataservices/supported_software): Information about the software and tools supported by NYU.
- [RStudio IDE Documentation](https://docs.posit.co/ide/user/): A guide to the RStudio interface and its features.
- [gtsummary R Package](https://cran.r-project.org/web/packages/gtsummary/index.html): Documentation for creating summary tables in R.
- [R for Data Science](https://r4ds.hadley.nz/): A free online book for learning how to organize, analyze, and visualize data using R.