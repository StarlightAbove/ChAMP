# ChAMP Package for DNA methylation analysis

> Note that this is NOT a proper release version ChAMP and under intensive modification and upgrade, the formally released one is on [Bioconductor](https://www.bioconductor.org/packages/release/bioc/html/ChAMP.html).

ChAMP package is designed for conduct DNA methylation array analysis, providing service from data loading, to final gene set enrichment analysis .e.g.

More information could be find in [Bioconductor page](https://bioconductor.org/packages/release/bioc/html/ChAMP.html). Also we provided a more detailed guide in the [HTML vignette](https://bioconductor.org/packages/release/bioc/vignettes/ChAMP/inst/doc/ChAMP.html).

Currently, ChAMP package is maintained by [YuanTian1991](https://github.com/YuanTian1991), if you met any problem during using the software, please email: champ450K@gmail.com

Install Code:

```
git clone https://github.com/YuanTian1991/ChAMP.git
R CMD INSTALL ChAMP
```


Current latest version: `2.29.1`, which support EPICv2, but it must be used along with [ChAMPdata >= 2.23.1](https://github.com/YuanTian1991/ChAMPdata)

# Warning
This is an experimental package version built by Eliza Kishan for internal use at the Przybyl Lab. This version is incredibly unstable and only used to debug and develop fixes for frequent errors within the package observed in more recent versions of R. Using this code with its modifications is HIGHLY unlikely to work on all machines and has not been experimentally tested yet. Download at your own risk. More stable versions are available on Bioconductor and I would suggest that those are used. 
