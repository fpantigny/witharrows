# Readme for the package witharrows

Author: F. Pantigny (`fpantigny@wanadoo.fr`).

CTAN page: `https://ctan.org/pkg/witharrows`

## License
The extension `witharrows` for TeX and LaTeX is distributed under the LPPL 1.3 license.

## Presentation

The LaTeX package `witharrows` provides environments `{WithArrows}` and `{DispWithArrows}`
similar to the environments `{aligned}` and `{align}` of `amsmath` but with the possibility to draw arrows on the right side of the alignment. These arrows are usually used to give explanations concerning the mathematical calculus presented.

This package can be used with xelatex, lualatex, pdflatex but also by the classical workflow latex-dvips-ps2pdf (or Adobe Distiller).

The extension `witharrows` can also be used with plain-TeX.



## Installation

The package `witharrows` is present in the distributions MiKTeX, TeX Live and MacTeX.

For a manual installation:

* put the files `witharrows.ins` and `witharrows.dtx` in the same directory; 
* run `latex witharrows.ins` in that directory.

The files `witharrows.sty` and `witharrows.tex` will be generated.

The file `witharrows.sty` is the only file necessary to use the extension `witharrows` with LaTeX (with `\usepackage{witharrows}`). You have to put it in the same directory as your document or (best) in a `texmf` tree. 

The file `witharrows.tex` is the only file necessary to use the extension `witharrows` with plain-TeX (with `\input{witharrows}`). You have to put it in the same directory as your document or (best) in a `texmf` tree. 

For the documentation in English, run: `lualatex witharrows.dtx` (several compilations are required).

For the documentation in French, run: `lualatex witharrows-french.tex`
