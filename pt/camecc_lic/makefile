all: camecc_lic slide

camecc_lic: camecc_lic.text
	-pdflatex -interaction nonstopmode -shell-escape camecc_lic
	-bibtex camecc_lic
	-pdflatex -interaction nonstopmode -shell-escape camecc_lic
	-pdflatex -interaction nonstopmode -shell-escape camecc_lic

slide: slide01 slide02 slide03 slide04


slide01: slide01.tex
	-pdflatex -interaction nonstopmode -shell-escape slide01
	-bibtex slide01
	-pdflatex -interaction nonstopmode -shell-escape slide01
	-pdflatex -interaction nonstopmode -shell-escape slide01

slide02: slide02.tex
	-pdflatex -interaction nonstopmode -shell-escape slide02.tex
	-bibtex slide02
	-pdflatex -interaction nonstopmode -shell-escape slide02.tex
	-pdflatex -interaction nonstopmode -shell-escape slide02.tex

slide03: slide03.tex
	-pdflatex -interaction nonstopmode -shell-escape slide03.tex
	-bibtex slide03
	-pdflatex -interaction nonstopmode -shell-escape slide03.tex
	-pdflatex -interaction nonstopmode -shell-escape slide03.tex

slide04: slide04.tex
	-pdflatex -interaction nonstopmode -shell-escape slide04.tex
	-bibtex slide04
	-pdflatex -interaction nonstopmode -shell-escape slide04.tex
	-pdflatex -interaction nonstopmode -shell-escape slide04.tex
