CC=pdflatex
BIB=bibtex
NAME=Raul_Reguillo_Carmona_Actividad_3

all : $(NAME).tex $(NAME).bib
	$(CC) $(NAME).tex
	$(BIB) $(NAME).aux
	$(CC) $(NAME).tex
	$(CC) $(NAME).tex

clean : *~
	rm *~
