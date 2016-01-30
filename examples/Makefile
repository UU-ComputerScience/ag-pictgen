PICTGEN=../dist/build/ag-pictgen/ag-pictgen

cons_toc_use.pdf: cons_toc_use.tex cons_toc.tikz
	latexmk -pdf $<

cons_toc.tikz: cons_toc.ppd
	$(PICTGEN) $< $@

