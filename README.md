## How to build

Building is very straightforward, you will need LaTeX and Git.
The following command will create a local copy of the source code for you.

`git clone https://github.com/anton-petrunin/invitation.git`

Go to the created folder and pun `pdflatex` and `makeindex`:

`cd invitation/`<br/>
`pdflatex invitation.tex`<br/>
`makeindex invitation`<br/>
`pdflatex invitation.tex`

If you want to use Springer's style, do 

`pdflatex invitation-springer.tex`
