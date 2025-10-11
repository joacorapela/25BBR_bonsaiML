all: application.pdf

# application.pdf: application.tex vision.tex approach.tex offlineMethods.tex rtmlMethods.tex visualExploration.tex offlineSpikeSorting.tex onlineSpikeSorting.tex projectMgmt.tex projectPartners.tex trustedResearchAndInnovation.tex rri.tex teamAdditions.tex teamComposition.tex r4riModules.tex team.tex module1.tex module2.tex module3.tex module4.tex dataManagement.tex
application.pdf: application.tex
	pdflatex application.tex
# 	bibtex bu1
# 	bibtex bu2
# 	pdflatex application.tex
# 	pdflatex application.tex

clean:
	rm application.aux application.log application.out application.toc bu1.aux bu2.aux
