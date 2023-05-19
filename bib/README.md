# How to use bibliography.bib file in your .tex document

```tex
% Add this include to your packages
\usepackage[style=numeric-comp,useprefix,hyperref,backend=bibtex,natbib,sorting=none]{biblatex}
```
```tex
% Put these line of code before the \begin{document} command.
\addbibresource{./bib/bibliography.bib}
\defbibheading{bibliography}{\subsection*{Bibliography}}
\defbibheading{sitography}{\subsection*{Sitography}}
```
```tex
% Put this line of code in the \begin{document} section where you want to print the bibliography page
\printbibliography[heading=bibintoc]
```
- Alright! You're ready to start using the bibliography file! 
