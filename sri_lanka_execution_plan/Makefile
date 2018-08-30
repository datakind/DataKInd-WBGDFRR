.DEFAULT_GOAL := build

help:
	@echo ""
	@echo "Available Tasks:"
	@echo "	clean					Clean directory and remove intermediate files"
	@echo "	build					Compile and build latex file"

build:
	@echo "Compiling latex file to pdf ..."
	pdflatex --shell-escape sri_lanka_execution_plan.tex

clean:
	@echo "Cleaning Directory ..."
	rm -f *.log *.bak *.aux *.bbl *.blg *.idx *.toc *.out *~

clean-all:
	rm -f *.dvi *.log *.bak *.aux *.bbl *.blg *.idx *.ps *.eps *.pdf *.toc *.out *~
