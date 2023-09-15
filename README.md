# GuessWho-SFEIR-LaTeX
LaTeX code to generate cards for the Guess Who board game
A dedicated thanks to SFEIR Belgium company for their support and warm welcome about this idea and its realization

## How to compile 
A Docker container can be used to generate the pdf without installing LaTeX
Go to the project directory then launch a container by mapping current volume.

    GuessWho-SFEIR-LaTeX$ sudo docker run -v .:/data -it geektortoise/latex:20.04 /bin/bash
then

    root@3469da82e3cb:/data# pdflatex main.tex 
    
Note that, for licence reason, I didn't integrate the images. You can mainly find them on [devicon.dev](https://devicon.dev/) (and you can give them a star ;-) ).

