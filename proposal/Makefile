pdf: paper.pdf

paper.ps: *.tex *.bib 
	rubber --ps paper

clean:
	rm -f paper.dvi paper.ps paper.pdf paper.aux paper.log paper.blg paper.bbl

paper.pdf: paper.ps
	rubber --ps --pdf paper
