all: ./activities.svg

%.svg: %.dot
	dot -Tsvg $*.dot > $*.svg
	~/bin/mySVG2PNG $*.svg
