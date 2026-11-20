# Overview {-}

<!-- badges: start -->
[![NIH NIAID grant](https://img.shields.io/badge/NIH_NIAID-R01AI180382-blue)](https://reporter.nih.gov/project-details/11392983)
<!-- badges: end -->

This respository analyzes human respiratory epithelial cells and lung
macrophages treated with estradiol (E2) and infected with influenza A
virus (IAV) described in aim 2 of the R01AI180382 grant.

```r
# Install the dependencies:
install.packages("pak")
pak::local_install_dev_deps()

# Run the analysis.
rm(params); bookdown::render_book()

# Open the analysis.
browseURL(paste0("file://", file.path(getwd(), "_book", "index.html")))
```
