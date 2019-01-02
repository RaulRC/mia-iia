CC=pdflatex
BIB=bibtex
NAME=Raul_Reguillo_Carmona_Actividad_3

run: document

document: bib
	$(CC) $(NAME).tex

bib: document
	$(CC) $(NAME).tex
	$(BIB) $(NAME).aux
	$(CC) $(NAME).tex

clean: bib
	rm *~

show: clean
	evince $(NAME).pdf
