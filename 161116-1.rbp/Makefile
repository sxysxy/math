include ../Make.global_options

PDF=161116-1.pdf

.PHONY: clean

default: all

all: $(PDF)

%.pdf: %.tex
	$(LATEX) $(LATEXFLAG) $< > /dev/null 2>&1

clean:
	$(RM) $(RM_FLAG) $(LATEX_CLEAN) $(PDF)
