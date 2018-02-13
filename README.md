# phd-thesis-dissertation
My Ph.D. thesis/dissertation on auroral tomography, sensor fusion, machine learning.
It fits the Boston University Librarian's specifications, including:
* margins, fonts, etc. fit his ruler to his satisfication as viewed on his scaled computer monitor.
* citation style, he checked the format of each and every one.

Writing time: ~ 6 workweeks.
Should be 312 PDF pages (including all the front matter unnumbered pages).

Prereq
======
I kept things as simple as possible. 

* Linux: `apt install pdflatex bibtex texlive-science texlive-font-utils`
* Windows: use [TeXStudio](https://www.texstudio.org/), which auto-installs needed packages as they're called
* Mac: `brew install texstudio`

Usage
=====
The typical Latex->PDF process. Hit the Build & View button in your GUI, or from the command line:

```sh
pdflatex thesis
bibtex thesis
pdflatex thesis
pdflatex thesis
```
