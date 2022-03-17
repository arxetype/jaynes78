# Retypeset of E.T Jaynes (1978). *Where do we stand on Maximum Entropy?*

Find the original source here: [https://bayes.wustl.edu/etj/articles/stand.on.entropy.pdf](https://bayes.wustl.edu/etj/articles/stand.on.entropy.pdf)

If you find mistakes in content/typographical errors, please feel free to open an issue, or send in a pull request (if you working on something, please do let me know so there aren't any redundant changes).



### LaTeX-specific comments
* I have built the PDF using pdflatex. Using XeLaTeX/LuaLaTeX may or may not give better results depending on how compatible `microtype` is with them.
* The font I chose to use in the project was Cochineal (available on CTAN as `cochineal`). If you prefer, you can build the source code with the default  
Computer Modern, or `mlmodern` (I personally prefer how this looks to the default). However, you'll need to add the following lines to compile:
 
    ```
    \newcommand{\uppi}{\pi}
    \newcommand{\lfstyle}{\relax}
    ```
They are already in the source, commented out (perhaps the font changing can be handled in a better manner).
* Sectioning and formatting is not the same as the original source (which is a bit limited since it was probably made with a typewriter). Content, however, is very close to 1:1. Exceptions include
    * ~~Equation Numbering~~. Equation numbering now follows the original. A19 and B33 are skipped.
    * Corrected some equation formatting (for example, Equation D76: `x'\beta` -> `x'_\beta`)
    * Correction in the References: Jeffries -> Jeffreys
    * Headers have been changed to reflect the current section (instead of the author name).
* The bibliography is done manually. Partially because I wanted to retain the original bibliography, but also because I am too lazy to actually go search all of these references, and make bib entries for each of them for a bib file, and then also make a bst file that replicates this style; the last point *might* even be impossible considering all of this was hand-typed. This was the quickest option, and it doesn't seem to have many issues (although I *do* miss `\citet` and `\citep`).



### Story Time
This project sprung from [an answer](https://mathoverflow.net/a/318973/478827) in a Mathoverflow thread that I came across a few months ago ([Old books you would like to have reprinted with high-quality typesetting](https://mathoverflow.net/questions/318839/old-books-you-would-like-to-have-reprinted-with-high-quality-typesetting)). The answer is reproduced verbatim below:

> It's more of a book-length paper than an actual book, but I always wanted a LaTeX version of E. T. Jaynes' [where do we stand on maximum entropy?](https://bayes.wustl.edu/etj/articles/stand.on.entropy.pdf). 
> I retyped about 20% of it myself at some point, but never finished the project.


Seeing as how it was only about 100 pages long (rather than say 400 pages like some of the other answers; maybe one day) and that I understood the first few pages at least, I took it up.

More projects may be added in the future.