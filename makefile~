# makefile responsible for building the paper.  PDF = pdflatex
COMPILER = pdflatex
READER = open 
BIBTEX = bibtex

exit : view 
	exit

view : compile main.pdf
	$(READER) main.pdf &

compile : main.tex
	$(COMPILER) main.tex
	$(BIBTEX) main
	$(BIBTEX) main
	$(COMPILER) main.tex
	$(COMPILER) main.tex
