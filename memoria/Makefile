default: thesis

plan:
	latexmk -pdf plan

thesis:
	latexmk -pdf --shell-escape thesis

tectonic:
	tectonic -Z shell-escape --keep-intermediates thesis.tex

.PHONY: all clean

all:
	latexmk -pdf plan
	latexmk -pdf --shell-escape thesis

clean:
	latexmk -pdf -C plan
	latexmk -pdf -C thesis
	rm -rf _minted-thesis
	rm -f *~ *.bbl *.maf *.mtc* *.xml *.loa *.lol
	rm -f thesisText/*~ thesisText/*.aux
	rm -f planText/*~ planText/*.aux
