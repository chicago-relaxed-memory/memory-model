paper:
	rm  -f main.pdf
	latexmk --pvc --pdf --halt-on-error main.tex
	killall Skim
clean:
	latexmk -c
publish:
	cp corrigendum.pdf ${HOME}/Public/papers/2020-oopsla-corrigendum.pdf && (cd ${HOME}/Public; make)
