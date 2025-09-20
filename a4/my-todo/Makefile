# Makefile to compile article.tex into article.pdf

article.pdf: article.tex
	pdflatex article.tex
	pdflatex article.tex  # Run twice for proper layout if needed

clean:
	rm -f *.aux *.log .out *.toc *.pdf
