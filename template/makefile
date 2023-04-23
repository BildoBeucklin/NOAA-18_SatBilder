.PHONY: all
all:
	pdflatex beleg.tex
	bibtex beleg
	pdflatex beleg.tex
.PHONY: git
git:
	git add .
	git commit -m "updating"
	git push
