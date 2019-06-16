## How to build

1. `git clone git@github.com:kevinstadler/compositionality.git`
2. download <https://github.com/IteratedStructure/MTurk/raw/master/Supplemental_Data_Size12.xlsx> and <https://github.com/IteratedStructure/MTurk/raw/master/Supplemental_Data_Size15.xlsx>
3. make sure your R installation has: `install.packages(c("knitr", "xtable", "cultevo", "gdata"))`
4. `knitr::knit2pdf("compositionality.Rnw")` (or from the shell: `Rscript -e 'knitr::knit2pdf("compositionality.Rnw")'`)
