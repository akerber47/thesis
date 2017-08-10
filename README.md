This is my Ph.D. dissertation. I used GitHub as my primary backup method while
writing it, and afterwards I decided to leave it up.

If you're unsure, you probably don't want to be reading it.

# Installation Instructions #

The implementation language is LaTeX with BibTeX. Once those are installed,
just run the usual rigmarole of commands:

	latex thesis.tex
	bibtex thesis.tex
	latex thesis.tex
	latex thesis.tex

to build the output document, thesis.dvi. As usual, if you want a pdf you
should use `pdflatex` instead of `latex` above.

Alternatively, I recommend using
[TeXShop](http://pages.uoregon.edu/koch/texshop/) and
[LyX](http://www.lyx.org/). With either of these, the one-click automatic build
should work perfectly.

# Implementation Details #

The UC Berkeley Ph.D. dissertation LaTeX document class is maintained by [Paul
Vojta](https://math.berkeley.edu/~vojta/tex/ucbthesis-phd.html).

Most images were drawn with [Pilot Precise v5 colored
pens](https://www.amazon.com/Pilot-Precise-Roller-Stick-Assorted/dp/B004E2O0DS/),
which I strongly recommend. Some later images were done in pencil. At some
point I planned to re-create or re-touch these images on a computer, but that
never happened.

This document wouldn't exist without a great many people. See the
acknowledgments inside for details.
