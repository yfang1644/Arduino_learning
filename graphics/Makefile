CMD     = inkscape
FLAGS   = -L pdf
.SUFFIXES: .svg .pdf
SVG     = $(wildcard *.svg)
PDF     = $(SVG:%.svg=%.pdf)
  
all: $(PDF)
  
.svg.pdf:
	$(CMD) $<  -A $@
