# Description

This repository contains the source code for the paper entitled
"Conflict, Cheap Talk, and Jespersen's Cycle" submitted to the journal
[Semantics & Pragmatics](https://semprag.org) by [Christopher Ahern](http://christopherahern.github.io/)
 and [Robin Clark](http://www.ling.upenn.edu/~rclark/Site/Welcome.html).


# Instructions

## Data

To obtain the data used in this analysis, clone
[this repository](https://github.com/christopherahern/jespersens-cycle-middle-english.git)
and follow the instructions listed there. Many thanks to
[Aaron Ecay](http://aaronecay.com/) and
[Meredith Tamminga](http://meredithtamminga.com/) for sharing the queries and code
to generate and process the data.

* The output of this results is currently also in `data/neg-data.csv`
* This means that the analysis can be run independently using just this repository

## Code

To run the code either download the files as a [ZIP](https://github.com/christopherahern/CCTJC/archive/master.zip),
 or clone the repository:

    git clone https://github.com/christopherahern/CCTJC.git

The output of the notebook [can also be viewed here](http://nbviewer.jupyter.org/github/christopherahern/CCTJC/blob/master/src/Ahern-Clark-SP-2017-Appendix.ipynb) without installing any additional software.


For running the code interactively we recommend installing the [Anaconda](https://www.continuum.io/downloads)
python distribution. To run the Jupyter notebook, run the following in `src/`:

    jupyter notebook

From there you can execute commands in order.

The appendix can be output to pdf using the following:

    jupyter nbconvert --to pdf Ahern-Clark-SP-2017-Appendix.ipynb 

The analysis can also be performed by running the following in `src/`:

    Rscript Ahern-Clark-SP-2017.R
    py Ahern-Clark-SP-2017.py

# Document

To compile the document, run the following in `tex/`:

    pdflatex Ahern-Clark-SP-2017.tex


# Citation

If you want to cite this paper, please use the following:

> Ahern, Christopher and Robin Clark. Conflict, Cheap Talk, and Jespersen's Cycle. 2017

If you reference the results of this paper, please also cite [the corpus](https://www.ling.upenn.edu/hist-corpora/citing-corpora.html)
 used:

> Kroch, Anthony, and Ann Taylor. 2000. The Penn-Helsinki Parsed Corpus of Middle English (PPCME2). Department of Linguistics, University of Pennsylvania. CD-ROM, second edition, release 4.


# Comments

If you have comments or questions about anything, feel free to email christopher.ahern@gmail.com
or [create an issue](https://github.com/christopherahern/CCTJC/issues) on github.
