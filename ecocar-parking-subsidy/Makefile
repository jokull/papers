clean:
	rm -f content.aux content.log content.pdf content.toc content.xdv

build:
	pandoc content.md -f markdown -H chapter_break.tex --standalone -o content.tex
	pdflatex -Vlang=icelandic content.tex
	rm -f content.aux content.log content.toc content.xdv content.tex
