CC=pdflatex
BIB=bibtex
NAME=Raul_Reguillo_Carmona_Actividad_3

document: $(NAME).tex
	$(CC) $(NAME).tex

bib: $(NAME).aux $(NAME).tex
	$(BIB) $(NAME).aux
	$(CC) $(NAME).tex
	$(CC) $(NAME).tex

clean:
	rm *~
