---
title: "Introduction"
teaching: 15
exercises: 0
questions:
- "What are basic principles for using spreadsheets for good data organization?"
objectives:
- "Understand how to organize data so computers can make the best use of the data"
keypoints:
- "Good data organization is the foundation of any research project."
---
### Credits
- Adapted from Data Carpentry Ecology Lesson (https://github.com/datacarpentry/spreadsheet-ecology-lesson) by: **Gail Clement** and **Donna Wrublewski**
- Authors of original Data Carpentry Ecology Lesson: **Christie Bahlai**, **Aleksandra Pawlik**<br>
- Contributors to original Data Carpentry Ecology Lesson: **Jennifer Bryan**, **Alexander Duryee**, **Jeffrey Hollister**, **Daisie Huang**, **Owen Jones**, **Clare Sloggett**, **Harriet Dashnow** and **Ben Marwick**



### Spreadsheet Overview

Good data organization is the foundation of any research project. Many curators and researchers maintain their data or perform data entry in spreadsheets. Spreadsheet programs are very useful graphical interfaces for designing data tables and handling very basic data
quality control functions. This lesson highlights best practices for maintainting data tables in spreadsheets to faciliate downstream enhancement and analysis, by both humans and machines.


### Spreadsheet Outline

In this lesson, we’re going to talk about:

- Good data entry practices - formatting data tables in spreadsheets
- How to avoid common formatting mistakes
- Dates as data - beware!
- Basic quality control and data manipulation in spreadsheets
- Exporting data from spreadsheets in plain text format(s) for use in other applications

Two relevant references for further information about tidy data and spreadsheet best practices we recommend:
- Wickham, Hadley. "Tidy Data" *Journal of Statistical Software* \[Online\], Volume 59, Issue 10 (12 September 2014). 	https://doi.org/10.18637/jss.v059.i10
- White, Ethan P. White, Baldridge1, elita, Brymn, Zachary T. et al. "Nine simple ways to make it easier to (re)use your data" *Ideas in Ecology and Evolution* \[Online\],  Vol 6, No 2 (2013). http://ojs.library.queensu.ca/index.php/IEE/article/view/4608, last accessed April 30, 2017.

*Overall good data practices*

Spreadsheets are good for data entry. Therefore we have a lot of data in spreadsheets. 
Much of your time as a researcher will be spent in this 'data wrangling' stage making sure that the data is complete, clean, consistent, and clearly organized so that subsequent steps in your research pipeline will go smoothly and accurately.
In this lesson we'll teach you how to think about data organization and some practices for more effective data wrangling.

### What this lesson will *not* teach you

- How to do *statistics* in a spreadsheet
- How to do *plotting* in a spreadsheet
- How to *write code* in spreadsheet programs

If you're looking to do the above processes, a good reference is
[Head First Excel](https://www.amazon.com/Head-First-Excel-learners-spreadsheets/dp/0596807694/ref=sr_1_1?ie=UTF8&qid=1491594584&sr=8-1&keywords=head+first+excel), published by O'Reilly

---

### Why aren't we teaching data analysis in spreadsheets

- Data analysis in spreadsheets usually requires a lot of manual
  work. If you want to change a parameter or run an analysis with a
  new dataset, you usually have to redo everything by hand. (We do
  know that you can create macros, but see the next point.)

- It is also difficult to track or reproduce statistical or plotting
  analyses done in spreadsheet programs when you want to go back to
  your work or someone asks for details of your analysis.

### Spreadsheet programs

Many spreadsheet programs are available. Since most participants utilize Excel as their primary spreadsheet program, this lesson will make use of Excel examples. There are others (gnumeric, Calc from OpenOffice, Google Sheets), and their functionality is similar, but Excel seems to be a program most commonly used by researchers.

Spreadsheets are popular researcher tools because they encompass a lot of the things we need to be able to do. We can use them for:
- Data entry
- Organizing data
- Subsetting and sorting data
- Statistics
- Plotting

## Limitations of Spreadsheets

Spreadsheets are good for data entry, but in reality we tend to
use spreadsheet programs for much more than data entry. We use them
to create data tables for publications, to generate summary
statistics, and make figures.

Generating tables for publications in a spreadsheet is not
optimal - often, when formatting a data table for publication, we’re
reporting key summary statistics in a way that is not really meant to
be read as data, and often involves special formatting
(merging cells, creating borders, making it pretty). We advise you to
do this sort of operation within your document editing software.

The latter two applications, generating statistics and figures, should 
be used with caution: because of the graphical, drag and drop nature of 
spreadsheet programs, it can be very difficult, if not impossible, to 
replicate your steps (much less retrace anyone else's), particularly if your 
stats or figures require you to do more complex calculations. Furthermore, 
in doing calculations in a spreadsheet, it’s easy to accidentally apply a 
slightly different formula to multiple adjacent cells. When using a 
command-line based statistics program like R or SAS, it’s practically 
impossible to apply a calculation to one observation in your 
dataset but not another unless you’re doing it on purpose. 

### Using Spreadsheets for Data Entry and Cleaning

In this lesson we're going to explore 5 primary spreadsheet practices:

1. [Formatting data tables in spreadsheets](../01-format-data/)
2. [Formatting problems](../02-common-mistakes/)
3. [Dates as data](../03-dates-as-data/)
4. [Quality control](../04-quality-control/)
5. [Exporting data](../05-exporting-data/)

