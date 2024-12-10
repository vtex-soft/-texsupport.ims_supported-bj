# texsupport.ims_supported-bj

## About

LaTeX author support files for IMS supported journal: 
[Bernoulli (BJ)](https://www.bernoullisociety.org/index.php/publications/bernoulli-journal/bernoulli-journal)

## Contents

The following files are given in the repository (or directly in `.zip` archive):

-   `imsart.cls`, `imsart.sty` - LaTeX style files designed for *IMS* supported journals articles. 
    Please do not change them. These files are already loaded in the template/sample files; 
-   `bj-template.tex` - the main template file should be used for article preparation;
-   `bj-sample.pdf` - instructions for the preparation of a
    camera-ready paper in LaTeX. This document contains useful information regarding the structure 
    of your document, proper tagging style, layout features, etc;
-   `figure1.eps`, `figure1.pdf` - sample figures for `bj-sample.pdf`;
-   `bj-sample.tex` - source file for the instructions paper `bj-sample.pdf`;
-   `imsart-nameyear.bst`, `imsart-number.bst` - BibTeX styles to prepare bibliography file.
    More information can be found [here](http://www.bibtex.org/Using/) 
    or [here](https://www.latex-tutorial.com/tutorials/bibtex/).

## Setup

-   Clone the repository or download the `.zip` archive;
-   Install LaTeX style files (`imsart.cls`, `imsart.sty`) in your TeX system or 
    place them in the same directory where your `*.tex` file is;
-   Read the instructions (`bj-sample.pdf`) for the preparation of your LaTeX document;
-   Use the template file `bj-template.tex` to prepare your manuscript.

## Tips

-   To remove frame from the text box use document class option `noshowframe`, e.g:

        \documentclass[bj,authoryear,noshowframe]{imsart}

## Bug reports

Please submit bug reports and/or feature requests
at [GitHub page](https://github.com/vtex-soft/texsupport.ims_supported-bj/issues) or 
[latex-support@vtex.lt](mailto:latex-support@vtex.lt).

