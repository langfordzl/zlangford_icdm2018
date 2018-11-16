SOURCE=zlangford_icdm_dmess2018

all:
	pdflatex $(SOURCE)
	bibtex $(SOURCE)
	pdflatex $(SOURCE)
	pdflatex $(SOURCE)

clean::
	rm -f $(SOURCE).aux $(SOURCE).blg $(SOURCE).out $(SOURCE).log $(SOURCE).bbl $(SOURCE).spl $(SOURCE).dvi $(SOURCE).pdf $(SOURCE).fff $(SOURCE).ttt
