[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3239516.svg)](https://doi.org/10.5281/zenodo.3239516)
[![Build status](https://ci.appveyor.com/api/projects/status/a0jlrsh3b8bl7u21?svg=true)](https://ci.appveyor.com/project/scivision/phd-thesis-dissertation)

# PhD Thesis in LaTeX

PDF uploads:

* [OpenBU](https://hdl.handle.net/2144/23382)
* [Zenodo](https://zenodo.org/record/3239516#.XPgg44hKhlY)

My Ph.D. thesis/dissertation on auroral tomography, sensor fusion, machine learning.
It fits the Boston University Librarian's specifications, including:

* margins, fonts, etc. fit his ruler to his satisfication as viewed on his scaled computer monitor.
* citation style, he checked the format of each and every one.

Writing time: ~ 6 workweeks.

Should be 312 PDF pages (including all the front matter unnumbered pages).

## Prereq

I kept things as simple as possible.

* Linux: `apt install texlive-latex-base texlive-bibtex-extra texlive-science texlive-font-utils`
* Windows: use [MiKTeX](https://miktex.org/download), which auto-installs needed packages as needed
* Mac: `brew cask install basictex`

## Usage

From the command line:

```sh
pdflatex thesis
bibtex thesis
pdflatex thesis
pdflatex thesis
```


## Style

Notice how chapters are broken up into multiple LaTeX files.
This enables easy diagnosis of such a large document.
