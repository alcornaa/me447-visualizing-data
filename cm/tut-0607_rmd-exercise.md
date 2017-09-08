
R markdown exercise
-------------------

1.  In your *design* directory, create a file called *D1\_temp.R*.
2.  In this file, write two lines of code
    `data(pressure)`
    `plot(pressure)`
3.  Run the file to make sure it produces a graph.
4.  In your *portfolio* directory, create an .Rmd script called *portfolio\_exercise.Rmd*
5.  In this file,
    -   change the document title to "Portfolio exercise"
    -   edit the name and date as needed
    -   change the output to Word
    -   delete everything below the header
    -   add the R setup code chunk including the knitr *root.dir=* argument and the *echo=* argument
    -   add a level-1 header called "D1 Scatterplot"
    -   write some prose explaining what you are doing in this exercise
    -   in a code chunk, use the *source()* function to import and execute the file *design/D1\_temp.R*

6.  Knit the file and debug if necessary until the Word document is created.
7.  Check the Word document. Revise the .Rmd script if necessary to hide the printing of the R code.

------------------------------------------------------------------------

[main page](../README.md)<br> [topics page](../README-by-topic.md)