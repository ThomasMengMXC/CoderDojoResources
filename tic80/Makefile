CC = pdflatex
CFLAGS = 
DIRECTORY = $(HOME)
SOURCES = $(wildcard *.tex)
OBJECTS = $(SOURCES:.tex=.pdf)

all: $(OBJECTS)

%.pdf : %.tex
	$(CC) $(CFLAGS) $<
	$(CC) $(CFLAGS) $<

clean:
	rm -f *.pdf *.log *.out *.toc *.snm *.nav *.aux
