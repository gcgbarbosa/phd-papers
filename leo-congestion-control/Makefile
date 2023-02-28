NAME=main
APPENDIX=appendix
OUTDIR=build

default: $(NAME).pdf

$(NAME).pdf: $(NAME).tex *.bib
	latexmk -outdir=$(OUTDIR) -pdf $(NAME).tex

#default: $(APPENDIX).pdf

#$(APPENDIX).pdf: $(APPENDIX).tex *.bib tex/*.tex fig/* table/*.tex
#	latexmk -outdir=$(OUTDIR) -pdf $(APPENDIX).tex

.PHONY: clean
clean:
	rm -rf $(OUTDIR)



