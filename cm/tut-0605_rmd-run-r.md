
run an R script from the Rmd script
-----------------------------------

In your portfolio .Rmd script, add a heading, for example,

<pre class="markdown"><code># D1 Scatterplot</code></pre>
Knit HTML to check that everything works as expected.

Add an R code chunk. Use the *source()* function to execute an R file that creates a graph. Here, the relative path shown assumes the .R script is saved in the *design* directory.

<pre class="r"><code>```{r D1, echo=FALSE}
source("design/name-of-file.R")
<code>```</code>
</code></pre>
-   `echo=FALSE` because the reader of your portfolio is generally not interested in the code
-   the *design* folder is where you should save all the R scripts that create the graphs in your portfolio. We'll discuss file management soon.
-   Knit HTML (or Word) to check that everything works as expected.

For drafting stages I prefer HTML output. Later we will cover how to manage Word Styles to customize the design of Word output documents.

Next tutorial: [adding prose to your portfolio](tut-0606_rmd-add-prose.md)

------------------------------------------------------------------------

[main page](../README.md)<br> [topics page](../README-by-topic.md)