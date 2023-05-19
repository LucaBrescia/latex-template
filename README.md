# Template for latex report

Download this repository to begin writing your report or thesis with an embedded ready-to-use frontespizio page from frontespizio package

## How to begin

- Rename the two "template" file with your preferences then compile it using the following command:
```sh
    # If you have PDFLATEX use
    pdflatex {yourname}.tex
```
```sh
    # If you want to use LATEX use
    latex {yourname}.tex
```
- Edit the {yourname}-frn.tex file first and compile it using the following command
```sh If you have PDFLATEX use
    pdflatex {yourname}-frn.tex
```
```sh
    # If you want to use LATEX use
    latex {yourname}-frn.tex
    dvips {yourname}-frn.eps {yourname}-frn
```
- And then recompile the main {yourname}.tex file
```sh
    # If you have PDFLATEX use
    pdflatex {yourname}.tex
```
```sh
    # If you want to use LATEX use
    latex {yourname}.tex
```
- Alright! You're ready to start editing the main file {yourname}.tex 

## Resources
In the res folder there are some useful document to begin with. 
In the bib folder there is also a bibliography template to include an automatic bibliography to your *.tex file. Remember to include the correct code to use automatic bibliography.
