---
layout: schedule
title: Schedule

base: 'https://github.com/lalmada1/Intro-to-Data-Science-Econ-4970/'

canvas:
  assignment_url: 'https://gastate.view.usg.edu/d2l/lms/dropbox/user/folders_list.d2l?ou=3531986&isprv=0'
  yellowdig_url: 'https://gastate.view.usg.edu/d2l/le/3531986/discussions/List'

lab-due-dates:
  lab-01: 'THUR Jan 29'
  lab-02: 'THUR Feb 5'
  lab-03: 'THUR Feb 19'
  lab-04: 'THUR Mar 12'
  lab-05: 'THUR Apr 2'
  lab-06: 'THUR Apr 16'

code-through:
  due-date: 'THUR Apr 30'
  
final-project:
  due-date: 'THUR Apr 23'

---

<!---
New sections start with 2 stars:  ** Section Title
New units start with 3 stars:     *** {Unit Metadata}
-----------------------------start example
** Section-I
*** { @unit = "15th Nov", @title = "Course Overview", @reading, @lecture, @assignment, @foldout }
-----------------------------end example
Unit Metadata is comprised of:
@unit - date or number
@title - unit name
@reading - turn on reading icon
@assignment - turn on lecture icon
@lecture - turn on lecture icon
@foldout - activate unit content (allow foldout)
Submit Buttons -
  <a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">Submit Lab</a>
  <a class="uk-button uk-button-primary" href="{{page.canvas.yellowdig_url}}">Discussion</a>
-->





<!---
#########################################
#########################################
##########
##########         WELCOME
##########
#########################################
#########################################
-->

** Welcome

*** { @unit = "", @title = "The R Toolkit", @reading, @lecture, @foldout }

## Introducing R

R is a 30-year-old statistical language created by New Zealand statisticians Robert Gentleman and Ross Ihaka as a free alternative to proprietary software for their students at the University of Auckland. In fact, its rich lineage can be directly traced to inventor and scientist Alexander Graham Bell.

Watch the video below for a brief introduction to R as it's used today.

<br>

<iframe src="https://player.vimeo.com/video/180644880" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<br>

## The R Toolkit

In this course we cover the foundations of data programming with the R language. In order to create robust and dynamic analysis we need to use a couple of tools that were built to leverage the power of R and create compelling narratives.

**RStudio** helps you manage projects by organizing files, scripts, packages and output. **Markdown** is a simple formatting convention that allows you to create publication-quality documents. **R Markdown** is a specific version of Markdown that allows you to combine text and code to create data-driven documents.

The following resources will help you get a better understanding of these tools.

* [Chapter 1: Core R](http://ds4ps.org/dp4ss-textbook/ch-010-core-r.html): Learning the basics of R

* [Chapter 2: RStudio](http://ds4ps.org/dp4ss-textbook/ch-020-rstudio.html): RStudio's functionality and features

* [Data-Driven Docs](http://ds4ps.org/dp4ss-textbook/ch-030-data-driven-docs.html): How R Markdown is used for interactive and dynamic reports

* [A Guide to Markdown](http://ds4ps.org/dp4ss-textbook/ch-031-markdown.html): How to use Markdown - the easy-to-learn formatting syntax

<br>

## Visualizing Tooling

Each tool you'll use in this course has a corresponding image, summarized below.

<br>

![](https://github.com/DS4PS/dp4ss-textbook/blob/master/figures/r-tools-overview.png?raw=true)

<br>

## R Markdown

You will get plenty of practice with these tools and submit your labs as knitted R Markdown (`.RMD`) files.

* Learn more about R Markdown here: [Getting Started with R Markdown](https://rmarkdown.rstudio.com/lesson-1.html)
* View R Markdown in action in the below image

<br>

[![](https://github.com/DS4PS/ds4ps.github.io/blob/master/gifs/NewCodeChunk/NewCodeChunk_media/NewCodeChunk.gif?raw=true)](../gifs/NewCodeChunk/NewCodeChunk.html)

<br>
<br>

*** { @unit = "", @title = "Videos", @lecture, @foldout }

<br>

## Getting to Know RStudio

RStudio is a graphical user interface (GUI) and integrated developer environment (IDE) that makes it much easier to use R for writing code, importing data, installing packages, and other features.

<br>

#### RStudio: A Guided Tour

The following video provides a tour of the RStudio interface and key components for getting started.

* What is RStudio?
* Executing and scripting commands
* Point-and-click and keyboard shortcuts
* Major interface components and features

<br>

<iframe width="560" height="315"
src="https://www.youtube.com/embed/xgPwDlAtuNI??rel=0&modestbranding=1&autohide=1&showinfo=0"
frameborder="0" allow="accelerometer;
autoplay; encrypted-media; gyroscope;
picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/xgPwDlAtuNI) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction & Defining Integrated Development Environments (IDE)
* (**00:41**) The Five Key Components of RStudio
* (**02:17**) Using the Console vs. Using Scripts
* (**04:29**) Shortcuts: Jumping Around, Full Screen, Saving
* (**05:27**) How to Save an R Script
* (**06:36**) Shortcuts: Moving Between & Exiting Scripts
* (**07:19**) "Session" & Setting Working Directories
* (**08:07**) Exporting Data as CSV Files
* (**09:04**) "Tools" & Customizing Your RStudio Interface
* (**10:02**) "Help" & Accessing Cheat Sheets
* (**10:42**) Global Environment & Objects
* (**13:20**) RStudio's Data Import Wizard
* (**14:35**) "Files" & Directory Contents
* (**14:57**) "Plots" & Graphics in R
* (**15:44**) "Help" & Documentation
* (**17:01**) Conclusions

<br>
<br>

## Easy Formatting with Markdown

Markdown is a "lightweight", easy-to-learn syntax that allows you to format language with boldface, italicization, bullet points, and more, even when there's no "rich content editor" menu available.  

Websites and applications that support Markdown may surprise you, including:

* Reddit
* GitHub
* RStudio
* OpenStreetMap
* Stack Exchange
* Microsoft Teams

<br>

#### Markdown Basics

The following video provides a brief introduction to Markdown fundamentals.

* Headers & Sub-Headers
* Boldface & Italicization
* Ordered & Unordered Lists
* List Sub-Items & Hyperlinks

<br>

<iframe width="560" height="315"
src="https://www.youtube.com/embed/oXgFrUq6btQ??rel=0&modestbranding=1&autohide=1&showinfo=0"
frameborder="0" allow="accelerometer;
autoplay; encrypted-media; gyroscope;
picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/oXgFrUq6btQ) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) What Is Markdown?
* (**01:17**) Demonstrating Markdown in RStudio
* (**02:00**) Typing Human-Readable Language
* (**02:27**) Creating Headers
* (**02:57**) Creating Sub-Headers
* (**04:35**) Formatting Boldface & Italicization
* (**05:58**) Creating Unordered & Ordered Lists
* (**07:04**) Creating List Sub-Items
* (**08:23**) Formatting Hyperlinks
* (**09:38**) Conclusion

<br>
<br>

## What Is R Markdown?

R Markdown is one of the most powerful tools you'll learn. It allows the synthesis of human language and code to perform processing and analysis tasks while explaining them to broad audiences.

<br>

#### R Markdown: An Introduction

The following video provides a tutorial and demonstration of R Markdown.

* Locating Lab Assignment Templates
* Creating New R Markdown Files
* The Benefits of R Markdown
* Customizing & Compiling
* Completing Assignments

<br>

<iframe width="560" height="315"
src="https://www.youtube.com/embed/ALwHaNzQub0??rel=0&modestbranding=1&autohide=1&showinfo=0"
frameborder="0" allow="accelerometer;
autoplay; encrypted-media; gyroscope;
picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/ALwHaNzQub0) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction & Contents
* (**00:22**) Locating R Markdown Templates
* (**01:20**) Creating a New R Markdown File
* (**02:36**) Machine- & Human-Readable Code
* (**05:41**) Creating & Formatting from Scratch
* (**06:19**) Creating Code Chunks
* (**07:37**) Code Chunk Options
* (**09:55**) Lab Templates
* (**12:25**) Discussion


<br>
<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Getting Started

The following checklist will help you organize and prepare for success in this course.

- [ ] [Read the Syllabus](https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/)
- [ ] [Install R](https://cran.rstudio.com/) and [R Studio Desktop](https://www.rstudio.com/products/rstudio/download/)
- [ ] Introduce Yourself in iCollege (See Below)
- [ ] (Recommended) Skim Readings
- [ ] (Recommended) Videos

<br>

*** { @unit = "{{page.discussion-dates.topic-00}}", @title = "Introduce Yourself", @assignment, @foldout }

<br>

## Introduce Yourself to the Class

Introduce yourself to the class:

1. A little about yourself
2. Your previous experience with data analytics
3. One thing you hope to do with your new skills in data analytics

<a class="uk-button uk-button-primary" href="{{page.canvas.yellowdig_url}}">Post to iCollege</a>

<br>
<br>








<!---
#########################################
#########################################
##########
##########         Unit 01
##########
#########################################
#########################################
-->

** Unit 1 - Functions and Vectors

*** { @unit = "", @title = "Unit Overview", @reading, @foldout  }

## Description

This unit introduces the most fundamental building blocks of data programming in R.

* **Vectors** are one or more values of the same type - each column in a table is a vector
* **Functions** are defined operations that transform individual or summarize multiple values
* **Objects** are named representations of values, datasets, functions, and other information
* **Assignment** is the act of naming and creating an object

## Learning Objectives

Once you have completed this unit, you will be able to:

1. Create new objects with assignment
2. Understand the basic anatomy and application of functions
3. Summarize vectors of various classes e.g. numeric, character, and logical

## Lab Assignment

Lab-01 is your first opportunity to combine human language and R code in R Markdown. You will practice using tax parcel data from Syracuse, NY (USA), including:

* Summarizing dataset characteristics, e.g. dimensions
* Use arithmetic functions to summarize and average data
* Determine the number of occurrences of qualitative data

### Functions

This assignment requires some combination of the following functions and operators:

* `names()`: Returns the variable names of a dataset
* `head()`: Returns the initial values of a dataset; default is 6 rows
* `$`: Extracts a variable from a dataset using `data$variable` syntax
* `length()`: Returnes the total number of values in a vector
* `dim()`: Returns the total rows and columns of a dataset, respectively
* `nrow()`: Returns the total rows of a dataset
* `ncol()`: Returns the total columns of a dataset
* `sum()`: Returns the sum of:
    - All values in a numeric vector
    - Total `TRUE` values of a logical vector
* `summary()`: Returns summary statistics for a dataset or individual vectors
* `table()`: Returns a tally of the number of occurrences of unique values in a vector

### Practice Data

This assignment uses Downtown Syracuse tax parcel data. View the documentation **[here](../labs/syr_parcels.html)**.

These data are imported using the following code.

```r
url <- "https://raw.githubusercontent.com/DS4PS/Data-Science-Class/master/DATA/syr_parcels.csv"
dat <- read.csv(url, stringsAsFactors = FALSE)

head(dat)
```

#### Downtown Syracuse

View the portion of Syracuse represented by these data.

![](https://github.com/DS4PS/dp4ss-textbook/blob/master/figures/downtown-syr.png?raw=true)

##### All of Syracuse

Syracuse, NY contains over 42,000 tax parcels.  Below depicts parcels with single family homes.

![](https://github.com/DS4PS/dp4ss-textbook/blob/master/figures/syracus-parcels.png?raw=true)

<br>
<br>

*** { @unit = "", @title = "Readings", @reading, @foldout  }

<br>

## Assigned Reading

Required reading for this unit includes:

1. **[Assignment](http://ds4ps.org/dp4ss-textbook/ch-033-calculator.html)**: Creating objects that represent data and operations
2. **[Functions](http://ds4ps.org/dp4ss-textbook/ch-040-functions.html)**: Data transforming or summarizing operations in R
3. **[Vectors](http://ds4ps.org/dp4ss-textbook/ch-050-vectors.html)**: Arrays of values of the same class, e.g. variables

The following background chapters are recommended for skimming for future reference:

1. **[Learning to Learn R](http://ds4ps.org/dp4ss-textbook/ch-032-learning_r.html)**: Preparing for lifelong learning in R
2. **[Core R](http://ds4ps.org/dp4ss-textbook/ch-010-core-r.html)**: The basics of vanilla R
3. **[RStudio](http://ds4ps.org/dp4ss-textbook/ch-020-rstudio.html)**: Components and features of RStudio
4. **[Data-Driven Docs](http://ds4ps.org/dp4ss-textbook/ch-030-data-driven-docs.html)**: Creating dynamic reports in R Markdown
5. **[Markdown](http://ds4ps.org/dp4ss-textbook/ch-031-markdown.html)**: Basic Markdown syntax

<br>

*** { @unit = "", @title = "Videos", @lecture, @foldout }

<br>

## Objects & Assignment

Play the video below for an overview of objects and assignment in R.

* How to open a new script in RStudio.
* Arithmetic and the order of operations.
* Creating different objects with assignments.
* Using objects algebraically and arithmetically.
* Common conventions and limitations in naming objects.

Visit the [chapter](http://ds4ps.org/dp4ss-textbook/ch-033-calculator.html).

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/q6kdjxSlq40?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/q6kdjxSlq40) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction
* (**00:36**) Clearing Your Console & Opening New Scripts
* (**00:58**) Arithmetic Operations in R
* (**03:38**) Order of Operations ("PEMDAS")
* (**05:30**) Creating Objects with Assignment
* (**07:00**) Assigning Multiple Values with `c()`
* (**08:12**) Assigning Tabular Data to Objects
* (**12:46**) Assigning Functions to Objects
* (**14:50**) Using Objects Algebraically
* (**16:20**) Object Naming Limitations
* (**17:17**) Common Object Naming Conventions
* (**21:03**) Be Consistent in Your Naming!
* (**21:33**) Conventions as "Calling Cards"
* (**24:00**) Conclusions

<br>

## Functions in R

Play the video below for an overview of functions in R.

* What are functions?
* Exploring function internals.
* How to create new functions in R.
* How to explore function documentation.
* What are function arguments and how are they used?

Visit the [chapter](http://ds4ps.org/dp4ss-textbook/ch-040-functions.html).

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/QoMX6ZauH5k?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/QoMX6ZauH5k) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction
* (**00:54**) What Are Functions?
* (**01:45**) Example of a Function: `mean()`
* (**03:16**) Meta-Functions without Specifications: `getwd()`
* (**04:56**) Package Functions: `read_csv()`
* (**05:12**) Running Functions without Required Specifications
* (**05:30**) Functions Under the Hood
* (**06:52**) How to Create New Functions
* (**09:45**) Function Documentation: `help()`
* (**10:24**) What Are Function Arguments?
* (**11:34**) Using Autocomplete & Tool Tips
* (**13:00**) Implicit (Unnamed) Argument Order
* (**14:39**) Importance of Argument Order
* (**16:58**) Default Argument Parameters
* (**19:41**) Exploring New Package Functions

<br>

## Understanding Vectors

Play the video below for an overview of vectors.

* What are they and how do you make them?
* What are some different kinds of vectors?
* What are common functions used for vectors?
* What are factors and why are they important in R?
* How do you change vector classes and what are some important nuances?

Visit the [chapter](http://ds4ps.org/dp4ss-textbook/ch-050-vectors.html).

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/2uavlW7Ytb8?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/2uavlW7Ytb8) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction
* (**00:57**) Reviewing Assignment & Objects
* (**00:57**) Reviewing Assignment & Objects
* (**01:31**) Creating Vectors with Function `c()`
* (**03:20**) Creating Integer Vectors
* (**04:07**) Creating Character Vectors
* (**04:50**) Creating Logical Vectors
* (**06:00**) Creating Sequences with `:`
* (**06:46**) Determining the Length of Vectors with `length()`
* (**09:06**) Determining Vector Classes with `class()`
* (**11:47**) "Casting" Vector Classes with `as.*()` Functions
* (**14:06**) What Are Factors?
* (**15:12**) An Example of Categorical Values
* (**15:45**) Specifying a Factor with `as.factor()`
* (**16:07**) Factor Levels in R
* (**16:48**) The Importance of Identifying Factors in R
* (**20:46**) Additional Casting, or `as.*()` Functions
* (**22:26**) Casting Data Structures with Data Frames
* (**24:25**) Casting as Matrices
* (**25:08**) Casting & Coercion
* (**27:52**) Differing Lengths & Recycling in R
* (**31:30**) Review & Conclusions

<br>

## Exploring Vectors

Play the video below for an overview of basic exploratory functions for a vector, i.e. a series of values.

* What constitutes tabular data?
* Extracting variables as a separate vector.
* Common functions for tables and variables.
* How to extract and store variables as objects.
* Exploratory and summarizing functions for vectors.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/6TF6UuM0IbI?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/6TF6UuM0IbI) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction
* (**00:38**) Starting a New Script
* (**01:23**) Practice Dataset 'mtcars'
* (**01:56**) Exploring Documentation in R
* (**03:22**) Anatomy of Tabular Data
* (**04:21**) Listing Variables with Function `names()`
* (**04:56**) Listing Column & Row Names
* (**05:32**) Dataset Dimensions with Function `dim()`
* (**05:56**) Row & Column Dimensions
* (**06:22**) Previewing First Observations with `head()`
* (**07:09**) Summarizing Dataset Structures with `str()`
* (**08:10**) Summarizing Structures with `glimpse()`
* (**09:31**) Extracting & Operating on Variables as Vectors
* (**11:20**) Storing Vectors as Objects
* (**11:32**) Determining Total Elements with `length()`
* (**12:28**) Summing Numeric Variables with `sum()`
* (**13:26**) Arithmetic Functions with Missing Values & `na.rm =`
* (**14:32**) Calculating Averages with Function `mean()`
* (**15:23**) Summarizing Vectors with Function `summary()`
* (**16:49**) Tallying Unique Values & Occurrences with Functions `unique()` & `table()`
* (**18:23**) Creating Crosstabs with Two Variables in `table()`
* (**19:56**) (**Optional**) Count & Proportion of `TRUE` with Function `mean()`

<br>
<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your First Unit

The following checklist will help you stay organized for this unit.

- [ ] Complete Assigned Readings: [Assignment](http://ds4ps.org/dp4ss-textbook/ch-033-calculator.html), [Functions](http://ds4ps.org/dp4ss-textbook/ch-040-functions.html), & [Vectors](http://ds4ps.org/dp4ss-textbook/ch-050-vectors.html)
- [ ] Complete & Submit [Lab 01](../units/01-building-blocks-of-r/lab-01-instructions.html) (See Below)
- [ ] (Recommended) Videos

<br>

<br>
<br>
<br>

*** { @unit = "{{page.lab-due-dates.lab-01}}", @title = "Lab 01", @assignment, @foldout  }

<br>

## Lab-01 - Practice with Vectors

This lab is designed to introduce you to basic functions that explore datasets and variables.

<a class="uk-button uk-button-default" onclick="window.open('../units/01-building-blocks-of-r/lab-01-instructions.html')">LAB-01 Instructions</a>

Click to access the lab templates. Modify and submit using the instructions.

<a class="uk-button uk-button-default" 
   onclick="window.open('https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/templates/')">
   LAB Templates
</a>


## Submit Solutions to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>

<br>
<br>










<!---
#########################################
#########################################
##########
##########         Unit 02
##########
#########################################
#########################################
-->


** Unit 2 - Operators and Descriptives

*** { @unit = "", @title = "Reflection", @reading, @foldout }

# Beginning

*Nobody tells this to people who are beginners, and I really wish somebody had told this to me.*

*All of us who do creative work, we get into it because we have good taste. But it's like there is this gap. For the first couple years that you're making stuff, what you're making isn't so good. It’s not that great. It’s trying to be good, it has ambition to be good, but it’s not that good.*

*But your taste, the thing that got you into the game, is still killer. And your taste is good enough that you can tell that what you're making is kind of a disappointment to you. A lot of people never get past that phase. They quit.*

*Everybody I know who does interesting, creative work they went through years where they had really good taste and they could tell that what they were making wasn't as good as they wanted it to be. They knew it fell short. Everybody goes through that.*

*And if you are just starting out or if you are still in this phase, you gotta know its normal and the most important thing you can do is do a lot of work. Do a huge volume of work. Put yourself on a deadline so that every week or every month you know you're going to finish one story. It is only by going through a volume of work that you're going to catch up and close that gap. And the work you're making will be as good as your ambitions.*

*I took longer to figure out how to do this than anyone I’ve ever met. It takes awhile. It’s gonna take you a while. It’s normal to take a while. You just have to fight your way through that.*

*—Ira Glass [on failure](https://jamesclear.com/ira-glass-failure)*

---

*It’s easy when you start out programming to get really frustrated and think, “Oh it’s me, I’m really stupid,” or, “I’m not made out to program.” But, that is absolutely not the case. Everyone gets frustrated. I still get frustrated occasionally when writing R code. It’s just a natural part of programming. So, it happens to everyone and gets less and less over time. Don’t blame yourself. Just take a break, do something fun, and then come back and try again later.*

*—Hadley Wickham on [advice to young and old programmers](https://www.r-bloggers.com/advice-to-young-and-old-programmers-a-conversation-with-hadley-wickham/)*

<br>
<br>

*** { @unit = "", @title = "Unit Overview", @reading, @foldout }

<br>

## Description

This section introduces logical statements used to create custom groups from your data.  

## Learning Objectives

Once you have completed this section you will be able to:
* translate human language phrases to a computer language
* create subsets of data

## Assigned Reading

Required:

[Group Construction with Logical Statements](http://ds4ps.org/dp4ss-textbook/p-050-business-logic.html)

## Lab

Lab-02 covers the following topics:

* Logical operators
* Group construction
* Descriptive statistics

<br>
<br>

*** { @unit = "", @title = "Readings", @reading, @foldout }

<br>

## Assigned Reading

Required:

[Group Construction with Logical Statements](http://ds4ps.org/dp4ss-textbook/p-050-business-logic.html)

<br>

*** { @unit = "", @title = "Videos", @lecture, @foldout }

<br>

## Logical Vectors

Play the video below for an overview of logical vectors, i.e. a series of `TRUE` and `FALSE` values.

* What are logical values?
* Creating logical vectors
* Using relational and logical operators
* Subsetting data with conditional statements

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/l9WhjLMMWH4?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/l9WhjLMMWH4) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction
* (**01:15**) What Is a Logical Vector?
* (**03:30**) Logicals "Under the Hood" & Arithmetic
* (**05:45**) Creating Logical Vectors with Conditions
* (**08:05**) Using Different Relational Operators
* (**12:06**) Multiple Conditions with Logical Operators
* (**18:07**) "Selector Vectors" & Subsetting Rows
* (**19:08**) Subsetting by Row & Column Positions
* (**23:13**) Assigning Position Indices to Objects
* (**25:57**) Notable Nuances of Logical Vectors
* (**27:00**) Finding & Replacing Values
* (**34:16**) Conclusions

<br>
<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your Second Unit

The following checklist will help you stay organized for this unit.

- [ ] Complete Assigned Readings: [Group Construction with Logical Statements](http://ds4ps.org/dp4ss-textbook/p-050-business-logic.html)
- [ ] Complete & Submit [Lab 02](../units/02-operators-and-descriptives/lab-02-instructions.html) (See Below)
- [ ] (Recommended) Explore Packages for [Code Through Project](../units/99-code-through/code-through-assignment.html)
- [ ] (Recommended) Videos

<br>
<br>

*** { @unit = "{{page.lab-due-dates.lab-02}}", @title = "Lab 02", @assignment, @foldout }

<br>
<br>

## Lab-02 - Constructing Groups

Read the following sections from the [course chapter on groups](http://ds4ps.org/dp4ss-textbook/p-050-business-logic.html) before starting the lab.

You will need a basic understanding of constructing groups and subsets in these sections.

* Logical Operators (1.1)
* Selector Vectors (1.2)
* Usefulness of Selector Vectors (1.3)
* Compound Logical Statements (2.1)  
* The Opposite-Of Operator (2.2)  

The rest of the chapter is useful information to come back to, but not needed for the lab.

*Similar to last week, the chapter highlights some easy ways to make errors with your code. We don't want to convince you that R is hard, but rather to ensure that you are paying attention to some subtle features of machine language that can impact your data.*

<a class="uk-button uk-button-default" onclick="window.open('../units/02-operators-and-descriptives/lab-02-instructions.html')">LAB-02 Instructions</a>

Click to access the lab templates. Modify and submit using the instructions.

<a class="uk-button uk-button-default" 
   onclick="window.open('https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/templates/')">
   LAB Templates
</a>

## Submit Solutions to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>

<br>
<br>








<!---
#########################################
#########################################
##########
##########         Unit 03
##########
#########################################
#########################################
-->

** Unit 3 - Visualization

*** { @unit = "", @title = "Reflection", @reading, @foldout  }

<br>

### Advice on Learning R

> People naturally go through a few phases. When you start out, you don’t have many tips and techniques at your disposal. So, you are forced to do the simplest thing possible using the simplest ideas. And sometimes you face problems that are really hard to solve, because you don’t know quite the right techniques yet. So, the very earliest phase, you’ve got a few techniques that you understand really well, and you apply them everywhere because those are the techniques you know.
>
> And the next stage that a lot of people go through, is that you learn more techniques, and more complex ways of solving problems, and then you get excited about them and start to apply them everywhere possible. So instead of using the simplest possible solution, you end up creating something that’s probably overly complex or uses some overly general formulation.
>
> And then eventually you get past that and it’s about understanding, “what are the techniques at my disposal? Which techniques fit this problem most naturally? How can I express myself as clearly as possible, so I can understand what I am doing, and so other people can understand what I am doing?” I talk about this a lot but think explicitly about code as communication. You are obviously telling the computer what to do, but ideally you want to write code to express what it means or what it is trying to do as well, so when others read it and when you in the future reads it, you can understand some of the reasoning.

~ Hadley Wickham [Advice to Young and Old R Programmers](https://www.r-bloggers.com/advice-to-young-and-old-programmers-a-conversation-with-hadley-wickham/)

<br>
<br>

*** { @unit = "", @title = "Unit Overview", @reading, @foldout }

<br>

## Description

This section introduces the Core R graphics engine.

## Learning Objectives

Once you have completed this section you will be able to:
* Use the plot() function
* Build custom graphics with base graphing commands:
  * points()  
  * lines(), abline()    
  * text()  
  * axis()  

## Assigned Reading

Required:

Please skim these chapters before starting your lab. Sample code has been provided for each lab question, but you may need the chapters and the R help files to find specific arguments.

[The plot() Function](http://ds4ps.org/dp4ss-textbook/p-061-plot-basics.html)  
[Building Custom Graphics](http://ds4ps.org/dp4ss-textbook/p-062-customized-graphics.html)

Suggested:

[Intro. to Data Viz](http://ds4ps.org/dp4ss-textbook/p-060-intro-to-data-viz.html)

*Help with R graphics:*

* [R Graph Gallery](https://www.r-graph-gallery.com/)  
* [R Graph Compendium](http://shinyapps.org/apps/RGraphCompendium/index.php)  
* [ggplot2 Geoms Gallery](https://ggplot2.tidyverse.org/reference/)  

*Inspiration:*

* [Makeover Mondays](http://www.makeovermonday.co.uk/gallery/)  
* [Flowing Data](http://flowingdata.com/)  
* [Junk Charts](http://junkcharts.typepad.com/junk_charts/)  
* [NYT Graphics Blog](http://kpq.github.io/chartsnthings/)  
* [Help Me Viz](https://twitter.com/HelpMeViz)  

## Lab

Lab-03 introduces the primary plotting functions used to build graphics.

* plot()  
* points()  
* lines(), abline()    
* text()  
* axis()  

The lab requires you to re-create a graph that was featured in the New York Times:

![](assets/img/pitcher-dominance.png)

<br>
<br>

*** { @unit = "", @title = "Readings", @reading, @foldout }

<br>

## Assigned Reading

Required:

[The plot() Function](http://ds4ps.org/dp4ss-textbook/p-061-plot-basics.html)  
[Building Custom Graphics](http://ds4ps.org/dp4ss-textbook/p-062-customized-graphics.html)

Suggested:

[Intro. to Data Viz](http://ds4ps.org/dp4ss-textbook/p-060-intro-to-data-viz.html)

<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your Third Unit

The following checklist will help you stay organized for this unit.

- [ ] Complete Assigned Readings: [The plot() Function](http://ds4ps.org/dp4ss-textbook/p-061-plot-basics.html) & [Building Custom Graphics](http://ds4ps.org/dp4ss-textbook/p-062-customized-graphics.html)
- [ ] Complete & Submit [Lab 03](../units/03-data-viz-static/lab-03-v1-instructions.html) (See Below)
- [ ] (Recommended) Read [Intro. to Data Viz](http://ds4ps.org/dp4ss-textbook/p-060-intro-to-data-viz.html)

<br>
<br>

*** { @unit = "{{page.lab-due-dates.lab-03}}", @title = "Lab 03", @assignment, @foldout  }

<br>
<br>

## Lab-03 - Graphics

This lab is designed to introduce you to core visualization functions by replicating an elaborate graphic.

We recommend you **skim** the chapters on graphing functions and custom graphics in R.

* [The plot() Function](http://ds4ps.org/dp4ss-textbook/p-061-plot-basics.html)  
* [Building Custom Graphics](http://ds4ps.org/dp4ss-textbook/p-062-customized-graphics.html)

Code is provided to get you started, but you will have to use documentation and the web to push the boundaries of your new knowledge of these functions.

<a class="uk-button uk-button-default" onclick="window.open('../units/03-data-viz-static/lab-03-v1-instructions.html')">LAB-03 v1 Instructions</a>
<!--
<a class="uk-button uk-button-default" onclick="window.open('../units/03-data-viz-static/lab-03-v2-instructions.html')">LAB-03 v2 Instructions</a>
-->

Click to access the lab templates. Modify and submit using the instructions.

<a class="uk-button uk-button-default" 
   onclick="window.open('https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/templates/')">
   LAB Templates
</a>
<!--
<a class="uk-button uk-button-default" onclick="window.open('../units/03-data-viz-static/lab-03-v2-template.rmd')">LAB-03 v2 Template</a>
-->

## Submit Solutions to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>

<br>
<br>






<!---
#########################################
#########################################
##########
##########         Unit 04
##########
#########################################
#########################################
-->

** Unit 4 - Dynamic Visualization

*** { @unit = "", @title = "Unit Overview", @reading, @foldout }

<br>

## Description

This section introduces the use of R Shiny **widgets** to make graphs dynamic.

## Learning Objectives

Dynamic graphics allow a user to select parameters that change the visualization in some way. Graphics will update in real-time within a web browser.

By the end of this unit you will be able to:

* Construct widgets to allow users to select inputs.
* Convert static graphics to dynamic graphics using the Shiny package.  

## Assigned Reading

Read the notes on using R Shiny **widgets** and **render** functions to accept user input (widgets), and change graphics in response (render).  

* [Notes on R Shiny](../units/04-data-viz-dynamic/topic-04x01-shiny-widgets.pdf)  
* [Example of a Dynamic Graph](https://shiny.rstudio.com/gallery/kmeans-example.html)  
* [Widgets Gallery](https://shiny.rstudio.com/gallery/widget-gallery.html)   

<br>

## Lab

Lab 04 will again use the graph that was featured in the New York Times:

![](assets/img/pitcher-dominance.png)

<br>

Try the [**interactive graphic**](https://archive.nytimes.com/www.nytimes.com/interactive/2013/03/29/sports/baseball/Strikeouts-Are-Still-Soaring.html) at the NYT.

<br>

But we will now add an input widget that allows users to select one team that will be highlighted on the graph in yellow.

<br>
<br>

*** { @unit = "", @title = "Readings", @reading, @foldout }

<br>

## Assigned Reading

Required:

* [Notes on R Shiny](../units/04-data-viz-dynamic/topic-04x01-shiny-widgets.pdf)
* [Example of a Dynamic Graph](https://shiny.rstudio.com/gallery/kmeans-example.html)
* [Widgets Gallery](https://shiny.rstudio.com/gallery/widget-gallery.html)

<br>

*** { @unit = "", @title = "Videos", @lecture, @foldout }

<br>

## Introducing Shiny

Play the video below for an overview of interactive graphics with Shiny.

* How to create a hard-coded graphic
* The logic behind making graphics dynamic
* An example of a dynamic Shiny app in RStudio
* How to create a new Shiny app with user inputs

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/UF7T7kAtetQ?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/UF7T7kAtetQ) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction
* (**00:38**) What Is a Shiny App?
* (**02:07**) Exploring Practice Data `faithful`
* (**03:24**) Recreating a Histogram of Wait Times
* (**04:59**) Adjusting Argument `breaks =` with "Hard" Values
* (**05:36**) Adjusting Argument `breaks =` with a Dynamic Values
* (**06:43**) Understanding Shiny Logic
* (**07:19**) Opening a New Shiny App
* (**08:41**) Cleaning RStudio's Example Shiny App
* (**09:43**) Comparing the App and Code
* (**10:25**) User Interfaces (UI)
* (**12:28**) Connecting Inputs (UI) with the Backend (Server)
* (**14:11**) Creating a New Shiny App
* (**15:01**) Connecting UI & Server-Side Plots ID
* (**15:32**) Using a New Input Widget - Radio Buttons
* (**16:55**) Creating a Dynamic Plot
* (**17:38**) Critical Arguments for Input Widget Functions
* (**19:43**) Inserting Server-Side Dynamic Values from User Inputs
* (**22:44**) Tying It All Together
* (**24:05**) Additional Notes
* (**25:13**) Conclusions

<br>
<br>

*** { @unit = "", @title = "Demo of Shiny Widgets", @reading, @foldout }

<br>
[Download Shiny Widgets Demo](https://cdn.rawgit.com/DS4PS/Data-Science-Class/53c986f1/TEMPLATES/ShinyWidgetsDemo.Rmd)

For more widget examples visit the [R Shiny Widget Gallery](https://shiny.rstudio.com/gallery/widget-gallery.html) and the [R Shiny Gallery](https://shiny.rstudio.com/gallery/).  

<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your Fourth Unit

The following checklist will help you stay organized for this unit.

- [ ] Complete Assigned Readings: [Notes on R Shiny](../units/04-data-viz-dynamic/topic-04x01-shiny-widgets.pdf), [Dynamic Graph Example](https://shiny.rstudio.com/gallery/kmeans-example.html), [Widgets Gallery](https://shiny.rstudio.com/gallery/widget-gallery.html)
- [ ] Complete & Submit [Lab 04](../units/04-data-viz-dynamic/lab-04a-instructions.html) (See Below)
- [ ] (Recommended) Videos
- [ ] (Recommended) Familiarize Yourself with the [Final Dashboard Project](../units/07-dashboards/lab-07-instructions.html)

<br>
<br>

*** { @unit = "{{page.lab-due-dates.lab-04}}", @title = "Lab 04", @assignment, @foldout  }

<br>
<br>

## Lab-04 - Dynamic Graphics

This lab is designed to introduce you to R Shiny by making last week's graphic interactive and dynamic.

<a class="uk-button uk-button-default" onclick="window.open('../units/04-data-viz-dynamic/lab-04a-instructions.html')">LAB-04 Instructions</a>

Click to access the lab templates. Modify and submit using the instructions.

**Note:** Rather than submitting a PDF or HTML file, please submit only the R or R Markdown file.  *Please ignore the boilerplate directions in this week's assignment*.


<a class="uk-button uk-button-default" 
   onclick="window.open('https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/templates/')">
   LAB Templates
</a>

## Submit Solutions to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>

<br>
<br>






<!---
#########################################
#########################################
##########
##########         Unit 05
##########
#########################################
#########################################
-->

** Unit 5 - Data Wrangling

*** { @unit = "", @title = "Unit Overview", @reading, @foldout }

<br>

## Description

This unit focuses on the important task of "**data wrangling**", various manipulations that allow you to quickly filter, join, sort, transform, and describe your data. The **dplyr** package and **tidyverse** tools are some of the most popular in R.

## Learning Objectives

By the end of this unit you will be able to:

* Subset data by rows or columns
* Create multi-dimensional summary tables by grouping data
* Generate new variables through transformations of existing variables
* Write efficient "data recipes" using pipe operators

## Assigned Reading

Read the notes on data wrangling in R:

* [Data Verbs in dplyr](http://ds4ps.org/dp4ss-textbook/p-070-data-verbs.html)  
* [Data Recipes Using Pipes](http://ds4ps.org/dp4ss-textbook/p-072-data-recipes.html)  
* [Efficient Use of Groups](http://ds4ps.org/dp4ss-textbook/p-073-group-structure.html)   

You may also find the [Data Wrangling Cheatsheet](https://rstudio.github.io/cheatsheets/html/data-transformation.html?_gl=1*hlmqwa*_ga*NTU4OTI2Mzc3LjE3NDA2ODQzNjg.*_ga_2C0WZ1JHG0*MTc0MjkwNzE3Ni4zLjEuMTc0MjkwNzQ1OC4wLjAuMA..) useful.

<br>

## Lab

Lab 05 will use data on traffic accidents in the City of Tempe:

[City of Tempe Open Data](https://data.tempe.gov/datasets/tempegov::1-08-crash-data-report-detail/about)  

<br>

![](assets/img/traffic-accidents.png)

<br>
<br>

*** { @unit = "", @title = "Readings", @reading, @foldout }

<br>

## Assigned Reading

Required:

* [Data Verbs in dplyr](http://ds4ps.org/dp4ss-textbook/p-070-data-verbs.html)  
* [Data Recipes Using Pipes](http://ds4ps.org/dp4ss-textbook/p-072-data-recipes.html)  
* [Efficient Use of Groups](http://ds4ps.org/dp4ss-textbook/p-073-group-structure.html)  

<br>

*** { @unit = "", @title = "Videos", @lecture, @foldout }

<br>

## Introducing dplyr

Play the video below for an overview of data manipulation with package **dplyr**.

* New syntax, e.g. bare variable names, piping
* Main "verbs" (functions) for data manipulation
* Helper "verbs" (functions) for added modification
* Examples of combining main and helper "verbs" in advanced expressions

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/M2QuERvxwm0?rel=0&modestbranding=1&autohide=1&showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

Visit the [video](https://youtu.be/M2QuERvxwm0) to navigate using timestamps in the description or bookmarks in the progress bar.

* (**00:00**) Introduction & About Package 'dplyr'
* (**02:12**) Opening RStudio & Creating Our Script
* (**02:35**) Loading Package 'dplyr'
* (**03:22**) An Example Expression Using 'dplyr' Verbs
* (**04:43**) The "Pipe Operator"
* (**05:46**) 'dplyr' Functions Without Pipe Operators
* (**07:48**) Bare Variable Names
* (**09:08**) Reviewing 'dplyr' Syntax
* (**09:46**) Main Verbs: `select()`
* (**14:44**) Main Verbs: `filter()`
* (**19:15**) Main Verbs: `arrange()`
* (**24:26**) Main Verbs: `mutate()`
* (**27:30**) Main Verbs: `summarize()`
* (**33:20**) Main Verbs: `group_by()`
* (**34:41**) `group_by()` & `mutate()` Operations
* (**37:37**) Don't Forget to `ungroup()`!
* (**39:04**) `group_by()` & `summarize()` Operations
* (**41:36**) Helper Verbs in 'dplyr', e.g. `desc()`, `pull()`
* (**44:25**) Putting It All Together

<br>
<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your Fifth Unit

The following checklist will help you stay organized for this unit.

- [ ] Complete Assigned Readings: [Data Verbs in dplyr](http://ds4ps.org/dp4ss-textbook/p-070-data-verbs.html), [Data Recipes Using Pipes](http://ds4ps.org/dp4ss-textbook/p-072-data-recipes.html), [Efficient Use of Groups](http://ds4ps.org/dp4ss-textbook/p-073-group-structure.html)
- [ ] Complete & Submit [Lab 05](../units/05-data-wrangling/lab-05-instructions.rmd) (See Below)
- [ ] (Recommended) Videos
- [ ] (Recommended) Begin Planning [Final Code-Through Project](../units/99-code-through/code-through-assignment.html)

<br>
<br>

*** { @unit = "{{page.lab-due-dates.lab-05}}", @title = "Lab 05", @assignment, @foldout  }

<br>
<br>

## Lab-05 - Data Wrangling

This lab offers practice analyzing traffic accident patterns using **dplyr** data wrangling functions.

**Note:** *These data and techniques will be used for your final project in building an interactive dashboard.*

<a class="uk-button uk-button-default" onclick="window.open('../units/05-data-wrangling/lab-05-instructions.html')">LAB-05 Instructions</a>

Click to access the lab templates. Modify and submit using the instructions.

<a class="uk-button uk-button-default" 
   onclick="window.open('https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/templates/')">
   LAB Templates
</a>

## Submit Solutions to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>

<br>
<br>




<!---
#########################################
#########################################
##########
##########         Unit 06
##########
#########################################
#########################################
-->

** Unit 6 - Data IO and Joins

*** { @unit = "", @title = "Unit Overview", @reading, @foldout }

<br>

## Description

This week has you continue practicing "**data wrangling**". This week will add the step of joining multiple datasets prior to analysis. We will continue to use the **dplyr** package.

## Learning Objectives

By the end of this unit you will be able to:

* Merge two related datasets using join functions
* Identify appropriate keys for joins
* Determine whether you need an inner, outer, or full join

![](assets/img/dplyr-joins.png)

## Assigned Reading

Read the notes on data joins:

* [Merging Data](http://ds4ps.org/dp4ss-textbook/p-076-merging-data.html)

For reference:

* [Manny Gimond's Page](https://mgimond.github.io/ES218/Week03c.html)  
* [Data Joins in dplyr](https://stat545.com/join-cheatsheet.html)  

<br>

## Lab

Lab 06 will use Lahman data on baseball for some [moneyball examples](https://towardsdatascience.com/linear-regression-moneyball-part-1-b93b3b9f5b53).

We will join the Salaries table to player bios (People table) and performance data (Batting and Fielding) to assess which characteristics predict salary and which teams have been able to most efficiently convert salary to wins.

<br>

![](assets/img/moneyball.jpg)

<br>
<br>

*** { @unit = "", @title = "Readings", @reading, @foldout }

<br>

## Assigned Reading

Read the notes on data joins:

* [Merging Data](http://ds4ps.org/dp4ss-textbook/p-076-merging-data.html)

<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your Sixth Unit

The following checklist will help you stay organized for this unit.

- [ ] Complete Assigned Readings: [Merging Data](http://ds4ps.org/dp4ss-textbook/p-076-merging-data.html)
- [ ] Complete & Submit [Lab 06](../units/06-data-joins/lab-06-instructions.rmd) (See Below)
- [ ] (Recommended) Begin [Final Code-Through Project](../units/99-code-through/code-through-assignment.html)
- [ ] (Recommended) Begin [Final Dashboard Project](../units/07-dashboards/lab-07-instructions.html)

<br>
<br>

*** { @unit = "{{page.lab-due-dates.lab-06}}", @title = "Lab 06", @assignment, @foldout  }

<br>
<br>

## Lab-06 - Data Joins

This lab is designed to introduce you to primary data join functions in R.

<a class="uk-button uk-button-default" onclick="window.open('../units/06-data-joins/lab-06-instructions.html')">LAB-06 Instructions</a>

Click to access the lab templates. Modify and submit using the instructions.

<a class="uk-button uk-button-default" 
   onclick="window.open('https://lalmada1.github.io/Intro-to-Data-Science-Econ-4970/templates/')">
   LAB Templates
</a>

## Submit Solutions to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>

<br>
<br>




<!---
#########################################
#########################################
##########
##########         FINAL PROJECTS
##########
#########################################
#########################################
-->

** FINAL PROJECTS

*** { @unit = "", @title = "Reflection", @reading, @foldout }

<br>

“With very few exceptions, there is no shortcut between not knowing something and knowing it. There is a beauty to awkwardness, a wisdom in the wobble.”

~Maya Stein

<br>

*** { @unit = "", @title = "Checklist", @assignment, @foldout }

## Your Final Projects Checklist

The following checklist will help you stay organized for the final projects.

- [ ] Finalize & Submit Your [Final Dashboard Project](../units/07-dashboards/lab-07-instructions.html)
- [ ] Finalize & Submit Your [Final Code-Through Project](../units/99-code-through/code-through-assignment.html)
- [ ] (Recommended) Submit a Course Evaluation

<br>


*** { @unit = "{{page.final-project.due-date}}", @title = "Final Dashboard Project", @assignment, @foldout  }

<br>

## Create a Data Dashboard in R

Working with the crash data from Lab-05, you will extend the work you began in Lab-04 by building on a dynamic data dashboard that will be used to explore and reveal insights in Tempe crash data.

<a class="uk-button uk-button-default" onclick="window.open('../units/07-dashboards/lab-07-instructions.html')">Final Project Instructions</a>

The following link downloads two templates:

* The entire dashboard, including all tabs
* A one-tab dashboard with helpful hints

We recommended creating new tabs independently, then incorporating them into the final dashboard.

<a class="uk-button uk-button-default" onclick="window.open('../templates')">Final Project Templates</a>

## Submit to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT DASHBOARD</a>

<br>
<br>

*** { @unit = "{{page.code-through.due-date}}", @title = "Code-Through Project", @assignment, @foldout  }

<br>

## Code-Through

Code-through instructions: 

<a class="uk-button uk-button-default" onclick="window.open('../units/99-code-through/code-through-assignment.html')">Code-Through Instructions</a>

Download the recommended template for your code-through with the below link.

**Note:** *This is one of many possible layouts; modify appropriately.*

<a class="uk-button uk-button-default" onclick="window.open('../units/99-code-through/code-through-template.rmd')">Base Code-Through Template</a>

## Submit to iCollege

<a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT CODE-THROUGH</a>

<br>
<br>


<style>
body {
   font-family: "Roboto", sans-serif;
}

p.italic {
  font-style: italic;
  color: black !important;
}
td {
  text-align: left;
}
td.i {
  text-align: center;
}
iframe {
  align: middle;
}
article {
  padding-left:20%;
}
em {
  color: black !important;
}
</style>
