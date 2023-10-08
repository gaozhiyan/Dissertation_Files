# Zhiyan Gao Dissertation LaTeX Templates

This repository contains LaTeX files for my 2019 dissertation titled "Weighing Phonetic Patterns in Non-Native English Speech." The format has received approval from [George Mason University's University Dissertation & Thesis Services](https://library.gmu.edu/udts). Feel free to use these LaTeX templates as a foundation for your own dissertation project.

Before diving into the LaTeX code, you can preview the appearance of the paper by visiting the [zhiyan_diss_main.pdf](https://github.com/gaozhiyan/Dissertation_Files/blob/master/zhiyan_diss_latex/zhiyan_diss_main.pdf) file. With the exception of two screenshots used in Chapters 4 and 5, everything else, including graphs and the bibliography, has been created using LaTeX code.

In Chapter 6, you'll notice that the three scatter plots have a 'ggplot' aesthetic. I generated these graphs using the 'ggplot2' package in R and then converted them into .tex files using the 'tikzDevice' package in R. This approach proved more convenient than learning how to create these scatter plots directly in LaTeX.

Chapter 3 features a few 'PRAAT' graphs displaying spectrograms and textgrids. These graphs were generated in 'PRAAT' and saved as .eps files to ensure optimal resolution.

### For Students Outside of CHSS

Please note that the cover page (signature sheet) is specifically designed for the College of Humanities and Social Sciences (CHSS). Other colleges/schools may have different cover page formats. Refer to the GMU Library [UDTS resources](https://library.gmu.edu/udts/resources) page for further details. Additionally, citation formats may vary depending on your field of study. If you require a different citation format, consult the documentation of the 'biblatex' package.

### For Linguistics Students

If you're pursuing linguistics, you'll likely work with IPA symbols. You can directly input IPA symbols into your .tex file, but be sure to compile (typeset) your document using XeLaTeX, as PDFLaTeX won't support it. If you prefer PDFLaTeX, consider using the 'tipa' package.

For those who need to create graphs (bar charts, scatter plots, confusion matrices, etc.), the 'pgfplots' package is essential. My dissertation includes bar graphs, so you can adapt the provided code to meet your requirements. Packages like 'forest' and 'qtree' are useful for drawing syntax trees.

If you'd rather not learn how to create graphs in LaTeX, you can create them in R using 'ggplot2' and then convert them to .tex files. Search for "ggplot2 to LaTeX" online for tutorials on how to do this using the 'tikzDevice' package in R.

### Other Considerations

Here are a few additional points to keep in mind:

- This is **NOT** a LaTeX tutorial. Please consult other sources for tutorials and guides.
- The provided LaTeX templates have been adapted from the GMU Library's LaTeX template. The original templates can be found [here](https://library.gmu.edu/udts/resources#templates).
- These LaTeX templates have been tested on MacBook OSX systems. Compatibility with Windows systems is uncertain.
- To compile (typeset) the files, use XeLaTeX and BibTeX.

<h2 align="center">
<span style="font-size:10em;">Best of luck with your dissertion! Let's go Patriots!</span>
</h2>
