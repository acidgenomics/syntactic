# syntactic

Make syntactically valid names out of character vectors.

## Installation

## Overview

[syntactic][] improves upon the `make.names()` functionality defined in base [R][], and is designed to return syntactically valid names from biological metadata. The package exports these primary functions:

- `camel()` (e.g. `helloWorld`).
- `dotted()` (e.g. `hello.world`).
- `snake()` (e.g. `hello_world`).
- `upperCamel()` (e.g. `HelloWorld`).

Additionally, the package exports these utility functions:

- `makeNames()`: modified variant of `make.names()` that sanitizes using underscores instead of dots.
- `capitalize()`: Capitalize the first letter of all words in a character vector.

[syntactic][] is designed to handle many common mixed case acronyms (e.g. mRNA, RNAi), as well as decimals in names. Additionally, the package defines S4 method support for a number of popular [Bioconductor][] S4 classes, including `DataFrame` and `GenomicRanges`.

## Related packages

If [syntactic][] doesn't work quite right for you, these popular packages also provide excellent sanitization support:

- [janitor][] by Sam Firke.
- [lettercase][] by Christopher Brown.
- [snakecase][] by Malte Grosser.

[Bioconductor]: https://bioconductor.org/
[janitor]: https://cran.r-project.org/package=janitor
[lettercase]: https://cran.r-project.org/package=lettercase
[R]: https://www.r-project.org/
[snakecase]: https://cran.r-project.org/package=snakecase
[syntactic]: https://steinbaugh.com/syntactic/