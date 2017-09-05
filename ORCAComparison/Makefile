summary.pdf: 
	pdflatex summary.tex
	pdflatex summary.tex
	bibtex summary
	pdflatex summary.tex
	pdflatex summary.tex

clean: 
	rm {*.aux,*.log,*.out,*.bbl,*.blg,*.pdf}
