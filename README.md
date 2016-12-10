# satzung-ffnord-verein
Unter Downloads befindet sich er Mitgliedsantrag als Latex dokument. Um Latex minimal zu installieren folgendes:

#Install texlive
    aptitude install texlive-fonts-recommended texlive-latex-recommended texlive-latex-recommended-doc_ texlive-pictures-doc_ texlive-latex-base-doc_ texlive-pstricks-doc_ texlive-latex-extra texlive-latex-extra-doc_ texlive-fonts-recommended-doc_ 

#Generieren

    latex Mitgliedsantrag.tex
    
ansehen mit:

    xdvi Mitgliedsantrag

    
#PDF

    pdflatex Mitgliedsantrag.tex
