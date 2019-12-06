## Zhiyan Gao Dissertation LaTex Codes

Included in the Repository are the LaTex files of my 2019 dissertation entitled "Weighing Phonetic Patterns in Non-Native English Speech". You are welcome to use the codes here as a template for your dissertation project.

You can check the [zhiyan_diss_main.pdf ](https://github.com/gaozhiyan/Dissertation_Files/blob/master/zhiyan_diss_latex/zhiyan_diss_main.pdf) file first to see how the paper looks. Except two screen-shots I used in Chapters 4 and 5, everything else including all other graphs and the bibliography are done with LaTeX codes. 

The 3 scatter plots in Chapter 6 has a ggplot feeling. It is because I drew these graphs using ggplot in R, and then used the <em>tikzDevice</em> package in R to convert it into .tex files. I did this because I want the font family and font size used in the graphs to be the same as the ones used for the main text. 

### Non-CHSS Students

The format has been approved by the GMU library. The cover page (i.e., the signature sheet) is for College of Humanities and Social Sciences (CHSS). Other colleges/schools have different cover page formants. See the GMU Library [UDTS resources](https://library.gmu.edu/udts/resources) page for details. 

### For students in the Linguistics program

First, change [this page](https://en.wikibooks.org/wiki/LaTeX/Linguistics) for LaTeX packages for linguistic purposes.

If you are working on linguistics, chances are you are going to use IPA symbols. You could directly type in IPA symbols in your .tex file. Just remember to compile (typeset) your file with XeLaTeX. PDFLaTeX won't work. If you insist on using PDFLaTex, then you need to use the <em>tipa</em> package.

If you are going to draw graphs (bar charts, scatter plots, confusion matrix, etc.), you are going to need the <em>pgfplot</em> package. I have bar graphs in my dissertation. So you can modify your the codes to suit your needs. Packages such as <em>qtree</em> is good for drawing syntax trees.

If you don't want to learn how to draw graphs in LaTex, you could actually draw your graph in R using <em>ggplot2</em>. Then convert the graph to a .tex file. Just google <em> gglot2 to latex </em>, there are tutorials on how to do this with the <em>tikzDevice</em> in R.

### Other Things

I am sharing all the codes here for whoever wants to reuse it. There are a few things you might want to know:

* This is **not** a tutorial of how to use LaTex. Please consult other sources for tutorials. 
* The codes here were modified based on the LaTex template provided by the GMU Library. The original codes are [here](https://library.gmu.edu/udts/resources#templates).
* The codes here were only tested on MacBook OSX systems. I have no idea if the codes also run on Windows systems.
