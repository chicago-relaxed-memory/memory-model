corrigendum:
	rm  -f corrigendum.pdf
	latexmk --pvc --pdf --halt-on-error corrigendum.tex
clean:
	latexmk -c
publish:
	cp corrigendum.pdf ${HOME}/Public/papers/2020-oopsla-corrigendum.pdf && (cd ${HOME}/Public; make)
