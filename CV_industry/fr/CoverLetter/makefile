CFLAGS = -Wall -std=gnu99
CFLAGS += `gsl-config --cflags`
LDLIBS += `gsl-config --libs`

default: main.pdf

main.pdf: main.tex  
	pdflatex $<
	pdflatex $< 



clean: ; $(RM) $(PLOTS)   main.aux main.log main.pdf

