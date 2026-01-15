## How to build

`cd mppics/`<br/>
`mpost pic.mp`<br/>
`cd ..`<br/>
`pdflatex invitation-CAT.tex`<br/>
`biber invitation-CAT`<br/>
`makeindex invitation-CAT`<br/>
`pdflatex invitation-CAT.tex`

Files for arXiv:

`tar -cvf arXiv.tar --files-from arXiv.txt`
