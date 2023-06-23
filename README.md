# preregRS

This package provides a RMarkdown template for __preregistrations__ with __research syntheses__ (preregRS).  
Authors are:

* [Jürgen Schneider](https://orcid.org/0000-0002-3772-4198)
* [Iris Backfisch](https://orcid.org/0000-0002-1363-9888)

Try it out with this jupyter notebook:  
<!-- badges: start -->
  [![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/j-5chneider/preregRS-jupyter/main?urlpath=rstudio)
  <!-- badges: end -->
Click on the button and open the 'preregRS.Rmd'.

## Installation

```r
install.packages("remotes")
remotes::install_github("j-5chneider/preregRS")
# Please report any installation bugs in the issues
```

## Usage

### Open Template

1. Install the package (see above)
2. Go to _File_ > _New File_ > _R Markdown..._
3. Choose _From Template_ and choose either _preregRS to HTML_ or _preregRS to PDF_

![](https://i.imgur.com/jlfUY6J.gif)

### Fill out Template

* We recommend to compile the .Rmd file first to get a glimpse at how the final preregistration will be structured (sections). Do this by hitting the "knit" button in RStudio.
* To get a better idea of what you can specify in each section, we included the original descriptions from the sources used (PRISMA-P, PROSPERO, MARS). Get this information by clicking the "more info" button in the compiled HTML or check out the tables under the section headings in the PDF.
* Start filling out the .Rmd template by replacing `_Put your text here._` with your information.
* Compile the .Rmd file to HTML (or PDF)
* Upload this preregistration protocol to a platform to make it publicly available with time stamp (e.g. [osf.io](https://osf.io/), [psycharchives.org](https://www.psycharchives.org/))

![](https://i.imgur.com/LgkJ4Rw.gif)

## Cite
__Publication__  
Schneider, J., Backfisch, I., & Lachner, A. (2022). Facilitating Open Science Practices for Research Syntheses: PreregRS Guides Preregistration. _Research Synthesis Methods, 13_(2), 284–289. https://doi.org/10.1002/jrsm.1540
 
  
__Presentation__   
Schneider, J., Backfisch, I., & Lachner, A. (2021). preregRS guides preregistration. Facilitating Open Science Practices for research syntheses. ZPID (Leibniz Institute for Psychology). https://doi.org/10.23668/PSYCHARCHIVES.4825


## Financial Statement
Supported by the Federal Ministry of Education and Research, Germany.
