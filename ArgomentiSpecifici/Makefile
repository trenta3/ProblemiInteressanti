# Makefile per la compilazione del progetto LaTeX
# Creato ven 20 mag 2016, 10.33.39, CEST

.PHONY: alldocuments ProprietaPolinomiali

alldocuments: 
	wget https://github.com/trenta3/stdmdoc/raw/master/stdmdoc.cls -O stdmdoc.cls
	pdflatex --shell-escape ProprietaPolinomiali.tex
	rm -f *.aux *.log *.out

ProprietaPolinomiali:
	wget https://github.com/trenta3/stdmdoc/raw/master/stdmdoc.cls -O stdmdoc.cls
	pdflatex --shell-escape ProprietaPolinomiali.tex
	rm -f *.aux *.log *.out

# Fine del Makefile
