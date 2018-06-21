# R
playground for R practices

# Installation guide:
1. Choose your preferrable [CRAN mirror](https://cran.r-project.org/mirrors.html) to download R
2. Installing the free R IDE [Rstudio](https://www.rstudio.com/products/rstudio/download/#download)

# Q & A:
Q: Warning messages on first start after download R ?
```
During startup - Warning messages:
1: Setting LC_CTYPE failed, using "C"
2: Setting LC_COLLATE failed, using "C"
3: Setting LC_TIME failed, using "C"
4: Setting LC_MESSAGES failed, using "C"
5: Setting LC_PAPER failed, using "C"
[R.app GUI 1.50 (6126) x86_64-apple-darwin9.8.0]

WARNING: You're using a non-UTF8 locale, therefore only ASCII characters will work. Please read R for Mac OS X FAQ (see Help) section 9 and adjust your system preferences accordingly. [History restored from /Users/nemo/.Rapp.history]
```
A: open terminal, run `defaults write org.R-project.R force.LANG en_US.UTF-8`, start R again.


# References:
- [Introduction to R](https://www.r-project.org/)
- [R FAQ](https://cran.r-project.org/doc/FAQ/R-FAQ.html) 
- [R MacOS X FAQ](https://cran.r-project.org/doc/FAQ/R-FAQ.html)
- [R Windows FAQ](https://cran.r-project.org/bin/windows/base/rw-FAQ.html)
- [Beginner's guide to R](https://www.computerworld.com/article/2497143/business-intelligence/business-intelligence-beginner-s-guide-to-r-introduction.html)
