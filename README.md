
# R Markdown to PowerPoint

You can render PowerPoint presentations from R Markdown documents. This capability is made possible by recent improvements to [Pandoc](http://pandoc.org/releases.html). See [Rendering PowerPoint Presentations with RStudio](https://support.rstudio.com/hc/en-us/articles/360004672913) for more information.

![](ppt-rmd.png)

### Features

You can generate most elements supported by Pandoc’s Markdown with the PowerPoint output including: Inline formatting, lists, LaTeX math expressions/equations, hyperlinks, block quotations,ß and more. PowerPoint output also supports these nice features:

* Images and tables
* Columns
* Speaker notes
* Templates

### RStudio v1.2

RStudio version 1.2 bundles Pandoc 2 making it easy to create PowerPoint presentations in R. You can upgrade to the latest version of RStudio by downloading and installing the [RStudio Preview](https://www.rstudio.com/products/rstudio/download/preview/).

### References

* [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/powerpoint-presentation.html)
* [Getting started](https://support.rstudio.com/hc/en-us/articles/360004672913-Rendering-PowerPoint-Presentations-with-RStudio)
* [Troubleshooting](https://support.rstudio.com/hc/en-us/articles/360006283914)
* [Community](https://community.rstudio.com/)
* [Submitting issues](https://github.com/rstudio/rmarkdown/issues)

See the [Pandoc manual](http://pandoc.org/MANUAL.html) for specific details. Note: If you want to change the slide size or design you should make those changes in a PowerPoint template and then include `reference_doc: mytemplate.pptx` in the YAML header.
