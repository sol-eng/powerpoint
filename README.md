
# R Markdown to PowerPoint

You can render PowerPoint presentations from R Markdown documents. This capability is made possible by recent improvements to [Pandoc](http://pandoc.org/releases.html). See this [Rendering PowerPoint Presentations with RStudio](https://support.rstudio.com/hc/en-us/articles/360004672913) for more information.

![](img/rmd2ppt.png)


### RStudio v1.2

RStudio version 1.2 bundles Pandoc 2 making it easy to create PowerPoint presentations in R. You can upgrade to the latest version of RStudio by downloading and installing the [RStudio Preview](https://www.rstudio.com/products/rstudio/download/preview/). This feature was announced on [community.rstudio.com](https://community.rstudio.com/t/quietly-announcing-the-powerpoint-support-in-r-markdown/8441). Documentation can be found in [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/powerpoint-presentation.html).

### Features

Most standard markdown formats are supported in the PowerPoint output (e.g. lists, images, links, quotes, math, inline formatting, etc.). Additionally, PowerPoint output support these nice features:

* Templates
* Columns
* Speaker notes
* Images and tables

See the [Pandoc manual](http://pandoc.org/MANUAL.html) for specific details. Note: If you want to change the slide size or design you should make those changes in a PowerPoint template and then include `reference_doc: mytemplate.pptx` in the YAML header.
