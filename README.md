# LaTeX Friendly Formatting

Renames the common formatting macros to make them more friendly.

## Usage

```latex
\documentclass{article}
\usepackage{friendlyformatting}

\begin{document}
  This is some text. \bold{This text is bold.} \italic{This text is italic.}
\end{document}
```

## Macros

 - `\bold`
 - `\italic`
 - `\smallcaps`
 - `\slanted`

## Installation

Git clone or download the package and then symlink it into the appropriate place
(different depending on os and laTeX distibution).

```shell
ln -s $PWD ~/Library/texmf/tex/latex/local
```

Alternatively, put the `friendlyformatting.sty` file next to your document.
