all: try11 try12 try21 try21 try31

try11: try11.tex
	-pdflatex -interaction nonstopmode -shell-escape try11
	-bibtex try11
	-pdflatex -interaction nonstopmode -shell-escape try11
	-pdflatex -interaction nonstopmode -shell-escape try11

try12: try12.tex
	-pdflatex -interaction nonstopmode -shell-escape try12.tex
	-bibtex try12
	-pdflatex -interaction nonstopmode -shell-escape try12.tex
	-pdflatex -interaction nonstopmode -shell-escape try12.tex

try13: try13.tex
	-pdflatex -interaction nonstopmode -shell-escape try13.tex
	-bibtex try13
	-pdflatex -interaction nonstopmode -shell-escape try13.tex
	-pdflatex -interaction nonstopmode -shell-escape try13.tex

try21: try21.tex
	-pdflatex -interaction nonstopmode -shell-escape try21.tex
	-bibtex try21
	-pdflatex -interaction nonstopmode -shell-escape try21.tex
	-pdflatex -interaction nonstopmode -shell-escape try21.tex

try31: try31.tex
	-pdflatex -interaction nonstopmode -shell-escape try31.tex
	-bibtex try31
	-pdflatex -interaction nonstopmode -shell-escape try31.tex
	-pdflatex -interaction nonstopmode -shell-escape try31.tex

clean: 
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.log
	rm -f *.out
