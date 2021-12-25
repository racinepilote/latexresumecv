# Racine Pilote LaTex CV / Resume

## What you need to install
You will need some Texlive distribution

### OS X / macOS 
install mactex throw brew install --cask mactex or visite [mactex](https://www.tug.org/mactex/)
```shell
  $ brew install --cask mactex 
```

### Other distribution or OS
[latex-project](https://www.latex-project.org/get/#tex-distributions)

If you want to generate txt file from latex file again with OS X / macOS 

your can install brew install pandoc and run the command [Pandoc](https://pandoc.org)

```shell
  $ brew install pandoc 
```
and run the command
```shell
  $ pandoc --to=plain --wrap=none main.tex
```


## How to build?

This repo also contains a texlive.profile file in the project root, that can be used to install the minimum required texlive packages when manually installing texlive.

### Build Procedure

   1. Run pdflatex main.tex (build/compile)
   2. The main.pdf should show the output.

```shell
  $ pdflatex main.tex
```
