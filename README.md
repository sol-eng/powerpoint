
# R Markdown to PowerPoint

You can render PowerPoint presentations from R Markdown documents. This capability is made possible by recent improvements to [Pandoc](http://pandoc.org/releases.html).

![](img/rmd2ppt.png)


### RStudio v1.2

RStudio version 1.2 bundles Pandoc 2 making it easy to create PowerPoint presentations in R. You can upgrade to the latest version of RStudio by downloading and installing the [RStudio Preview](https://www.rstudio.com/products/rstudio/download/preview/). This feature was announced on [community.rstudio.com](https://community.rstudio.com/t/quietly-announcing-the-powerpoint-support-in-r-markdown/8441). Documentation can be found in [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/powerpoint-presentation.html).

### Features

Most standard markdown formats are supported in the PowerPoint output (e.g. lists, images, links, quotes, math, inline formatting, etc.). Additionally, PowerPoint output support these nice features:

* Columns
* Templates (i.e. reference docs)
* Tables
* Code blocks with syntax highlighting
* Speaker notes

See the [Pandoc manual](http://pandoc.org/MANUAL.html) for specific details. Note: If you want to change the slide size or design you should make those changes in a PowerPoint template and then include `reference_doc: mytemplate.pptx` in the YAML header.

### Examples

This project contains several example presentations that demonstrate various PowerPoint capabilities. Start with the [PowerPoint Intro](http://colorado.rstudio.com:3939/powerpoint/getting-started.html) which gives an overview of Pandoc, R Markdown, and RStudio features.

* **Hello World**. Getting started with a simple example.
* **Widscreen Template**. Change the slide size and design of a presentation.
* **Slide Level**. Explicitly define the slide level.
* **Shiny Webshot**. Create a webshot of a Shiny app.
* **R Admin**. An example presentation from rstudio::conf 2018.

