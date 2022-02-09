## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

    us_counties = read.csv('https://raw.githubusercontent.com/jgscott/ECO395M/master/data/us_counties.csv')
    hist(us_counties$median_income2018)

![](trail_files/figure-markdown_strict/unnamed-chunk-1-1.png)

## Including Plots

You can also embed plots, for example:

![](trail_files/figure-markdown_strict/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
