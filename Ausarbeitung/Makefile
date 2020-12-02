# by Max-Heinrich Laves 2019
# laves@imes.uni-hannover.de

VERSION = 2019.1

default: all
all: 
	pdflatex main
	biber main
	pdflatex main
	pdflatex main

.PHONY : clean
clean:
	-rm -f main.aux \
	main.bbl \
	main.blg \
	main.bcf \
	main.log \
	main.nlo \
	main.out \
	main.pdf \
	main.run.xml \
	main.toc
