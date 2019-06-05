# PhD Thesis in LaTeX

My Ph.D. thesis/dissertation on auroral tomography, sensor fusion, machine learning.
It fits the Boston University Librarian's specifications, including:

* margins, fonts, etc. fit his ruler to his satisfication as viewed on his scaled computer monitor.
* citation style, he checked the format of each and every one.

Writing time: ~ 6 workweeks.

Should be 312 PDF pages (including all the front matter unnumbered pages).

## Prereq

I kept things as simple as possible.

* Linux: `apt install pdflatex bibtex texlive-science texlive-font-utils`
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
