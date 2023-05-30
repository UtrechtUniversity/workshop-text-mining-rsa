# README

This folder contains a template project for the final assignment of the course. Follow the instructions in this README file step-by-step and build up your project along the way.

## Project Structure

The project is structured in the following way:

05-final-assignment
├───05-final-assignment.Rproj
├───data
├───docs
├───lexicons
    ├─── NRC_lexicon.txt  
├───R
    ├─── yourstudentnumber-final-assignment.Rmd
└───README.txt

### R Project File

Always use the R Project file (05-final-assignment.Rproj) to open your project. This will automatically set the working directory, which is needed to work with some of the template code we will provide.

### Data

Place the dataset you export from I-Analyzer in the data folder. Make sure to (re)name the dataset as data.csv (note that csv is the file extension) because the name assigned by I-Analyzer to the export can be very long and messy. 

### Docs

Use the docs folder to place any supplementary materials such as notes etc.

### Lexicons

This folder already contains the NRC Lexicon (NRC_lexicon.txt) that you will use in your text-mining analyses.

### R

This folder contains the template R Markdown file for you to work on your assignment (yourstudentnumber_final-assignment.Rmd). Instructions on how to work with this template continue below in a separate section. Eventually, you will render this R Markdown file to HTML format.

## Assignment Template

We assume that you will start working with template after you have exported your dataset from I-Analyzer and placed it in the data folder. The remainder of this section walks you through on how to work with this template

### YAML

In the YAML (Yet Another Markup Language) section, which are the lines at the very beginning of the source document between three ---):

In the YAML session (the lines at the very beginning of the source document between three $-$):

-   Replace "My_assigment" with the title of your report, based on your research question/query;
-   Use your name and surname as author;
-   Change the date to the date of submission of your assignment.

## Markdown Format

You will write regular text using the Markdown format in your file. You can refer to this [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/). Moreover, you use the [Visual Editor](https://rstudio.github.io/visual-markdown-editing/) in RStudio to preview Markdown content as you go.

## Introduction

Here you will write a small introduction about your research question/query of maximum 400 words. Every introduction usually follows a funnel structure, from general to particular:

-   Introduce the topic (in general);
-   Then focus on your specific research question/query;
-   Explain how and why exploring your research question/query would be interesting;
-   Explain (in general) how the analysis you are going to perfrom can answer your research question/query.

## Data 

Here you will describe your data, including how you obtained it from I-Analyzer. Be sure to include the following information:

-   The corpus of data and eventual references associated with it;
-   Every single field you used in your I-Analyzer query; 
-   Any other information relative to the corpus and the analysis (data timeline etc.).

## Analysis & Results

This is the only section of your assignment template that will contain code. Before performing any analyses, write a few lines on the text-mining techniques you are going to apply and what kind of results you expect to obtain from the analysis. In other words, provide a very brief overview of your data analysis plan in about 100 words at maximum. 

As you move through this section, before every block of code, provide a couple of lines describing what the specific code block is intended to do. 

In some cases, we have provided some template code blocks, which you will have to adjust to suit your data - much like the exercises in class. As you go through the steps of analyzing your data, you will have to build the code blocks more independently (though you can always refer to the earlier course materials).

You can add code chunks as required by clicking the `Add Chunk` button. In case you need a reference, here is a link: [https://rmarkdown.rstudio.com/lesson-3.html](https://rmarkdown.rstudio.com/lesson-3.html)

After every code block, provide a couple of lines to describe the results of the operation. In some cases, it may be as simple as stating the number of values that were dropped after filtering NAs. In other cases, there may be more interesting output in the form of a table or plot. In this case, describe the results and interpret the findings in the context of your research question/query. Leave any conclusions for the next section. 

## Conclusion

Here you will summarize your analyses as a whole. What are your results and findings? What is your main conclusion (the short answer to your research question/query, if you found any. What are the possibilities of future analyses or studies to better explore the question/query.

## References

At minimum, you should include the following references:

1. The corpus your referred to in I-Analyzer
2. The textbook that was used for this course (Text-Mining with I-Analyzer & R).
3. The Text Mining with R: A Tidy Approach book.

## Render to HTML

When you are completed with your assignment and the code chunks are running smoothly, you can click the 'Knit' button in the RStudio menu to render/convert the R Markdown file to HTML format.


