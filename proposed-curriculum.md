#Matt's D.S. Curriculum outline

Proposed Videos/Lectures/Course





1. Git and Github
2. Lesson 2; Base R
    - "Let's get going with Base R?
    1. Load data
    2. Check data
    3. Visually Inspect data
    4. Model data
4. Exploratory Data Analysis
    - I plan to use Kaggle as my reference to see what the average EDA does.
    - What are the most common commands used in EDA.
    - SEE: https://www.kaggle.com/notaapple/detailed-exploratory-data-analysis-using-r
    - I would like to take a hands on approach. I'm toying with the title(s) of "Helpful EDA", "Getting EDA Done", "Your First Assignment", "Get Useful Data", "Become Useful in R Quickly"
    - Why does one Do EDA? What can you find?
    - Outline the steps for EDA
    - Outline Steps for section(s)
        - Abstract
        - Loading Libraries and Data, Load and check data
        - Check data w/ head, str, dim, glimpse, summary, is.na, sapply(ksdata, function(x) sum(is.na(x))), c(ncol(train),nrow(train))
        - colSums(is.na(df)), is.null(df), table(dtrain$is_attributed))
        - Missing values?, na.rm=(T,F), colSums(is.na(combine_train))
        - (Re)Naming Columns
        - Check for correlation(s),  cor(train$target, method = "spearman")
        - Graphics/scatterplots, histograms, line plots, boxplots, 
        - Find min, max, range, median, mean
5. Storing your data for others to see; RMD, Using Rpubs.com & Github & producing HTML or PDF, {png, pdf, jpg}&dev.off
    ---
    title: "Rossmann Exploratory Analysis"
    author: "Christian Thiele"
    date: "8. Oktober 2015"
    output: html_document
    ---
6. . RMarkdown;The simplest language you will love.
7. Linear Models; Relationships between x & y, Correlation, lm(), 

8. Move on to `skimr package` & `skim()`
9. HOW to make a CASE for Using R over Excel or SAS, SPSS, JUMP, etc.

## 1. Introduction to R/Getting Started with R

>This first course is intended to be a very basic intro to:

This set of videos is designed for the first time user of R.

I am a scientist by training but not a computer scientist or a statistician. Therefore I like numbers and playing with them. 

I am not a computer scientist, so I will start off with mindset of using this interesting tool.

Much like your own car, Most of us know how to drive it. Most of us do not know the theory behind engineering a car or even how to fix it when you are on the side of the road.

However, we all expect our cars to do certain things, accelerate when you press the gas pedal and steer in the direction we want to go.

R has been around for a 25-30 years. That's fine . But what does this mean? It means that over time many people have made additions to the BASE package. I believe in learning in steps. Learn the basics (or BASE package) first. Then move to packages that have that add more functionality. I have found that it is common to find more functionality can commonly mean more sophistication and details and complications.

1. How to install R
2. How to install RStudio
3. Layout of RStudio
4. Getting Help
5. Importing Your Own Data; `read.csv` & Import using RStudio Shortcut
7. Examine our Data; `str`
8. Finding more data
9. Projects
10. Files in R
11. Packages
12. Wrapping Up
13. Objects and Functions








## 2. Lesson 2; Base R


Course Content
Welcome Sample Lesson
RMarkdown
Why Use RMarkdown? Sample Lesson
RMarkdown Overview
YAML
Text
Code Chunks
Wrapping Up
Data Wrangling and Analysis
Getting Started
The Tidyverse
select
mutate
filter
summarize
group_by Sample Lesson
count
arrange
Create a New Data Frame
Crosstabs
Wrapping Up
Data Visualization
An Important Workflow Tip
The Grammar of Graphics
Scatterplots Sample Lesson
Histograms
Bar Charts
color and fill
scales
Text and Labels
Plot Labels
Themes
Facets
Save Plots
Wrapping Up
Wrapping Up
You Did It!








See: [Types of Data](https://i.stack.imgur.com/3QemG.gif)
