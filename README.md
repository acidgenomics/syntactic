# syntactic

[![Install with Bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-syntactic/README.html)

Make syntactically valid names out of character vectors.

## Installation

### [R][] method

```r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}
install.packages(
    pkgs = "syntactic",
    repos = c(
        "https://r.acidgenomics.com",
        BiocManager::repositories()
    )
)
```

### [conda][] method

Configure [conda][] to use the [bioconda][] channels.

```sh
# Don't install recipe into base environment.
name="r-syntactic"
conda create --name="$name" "$name"
conda activate "$name"
R
```

[bioconda]: https://bioconda.github.io/
[conda]: https://conda.io/
[r]: https://www.r-project.org/
