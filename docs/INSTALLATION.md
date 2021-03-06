## Install the R runtime
Visit the [CRAN homepage](https://cran.r-project.org/). There you will find download links for Linux, Mac OSX, and Windows. Download and run the installer for your operating system.

If you are using Windows, you may also need to install the [Rtools](https://cran.r-project.org/bin/windows/Rtools/) suite, as some packages may depend on it. Mac users may need to install XCode (particularly its command-line tools) for the same reason.

## Install the RStudio IDE
RStudio is a popular cross-platform integrated development environment (IDE) for programming in R (and also supports other languages like Python, JavaScript, and Markdown). Using RStudio will make writing your code solutions and running tests easier.

Download and install the [current stable version of RStudio](https://www.rstudio.com/products/rstudio/download/). Or, alternatively, get the [preview version](https://www.rstudio.com/products/rstudio/download/preview/) of an upcoming release.

## Install the R packages for running tests
The test runner for the specs is the [`testthat`](https://github.com/hadley/testthat) library from Hadley Wickham, which is a popular choice for R library authors. We also download the [`devtools`](https://github.com/hadley/devtools) library, which is necessary for some parts of the workflow.

To install these libraries, type the following in your RStudio console (or wherever you are using R).


```{R}
install.packages("testthat")
install.packages("devtools")
```

While it is unlikely that you will _need_ to install packages to solve the exercism problems, you may want to bring in a general-purpose utility packages like [`magrittr`](https://github.com/smbache/magrittr) that suit your programming style. To install and load a package like `magrittr`:

```{R}
install.packages("magrittr")
library(magrittr)
```
