# Checkpoint
## `Delete this readme or write your own version before starting checkpoints`
### `Leave the "Init" (the first) commit`
### `Refer announcement on iLMS` [HERE](http://lms.nthu.edu.tw/course.php?courseID=38045&f=news_show&newsID=1921658)
## Goal
Use LaTeX to make your own version for this target *[paper](https://ieeexplore.ieee.org/document/7417448)*.

## Time Schedule
### Checkpoint 1
#### - Due Date: Thu., May 9, 2019
#### - TO-DO
1. **Develop envorinment**: Set up develop env including but not limited to:  
    1. **Git**: Make sure you know how to use commands like *git-commit*, *git-push*, *git-pull*, etc.  
    2. **Editor**: Use *Texmaker* (for LaTeX) and *JabRef* (for BibTex) or any editors you're familiar with.  
    3. **Scripts**: Read and run both [4 scripts](https://github.com/LouisSung/LaTeX-Diff_Git) written by TA, at least `gen_diff`, which will use to grade your final project.  
       You would like to refer both readme and help-usage (e.g., `./0_init.sh -h`) to learn how to use these scripts.  
2. **Paper content**: Porting all the sentences in (sub)sessions from PDF to LaTeX format, including:  
    1. Title, Author, abstract, and keywords.  
    2. Introduction, background and related works, technical approah, implementation, evaluation, and conclusions.  
    3. Citations (references) using BibTex.  

---
### Checkpoint 2
#### - Due Date: Sun., May 12, 2019
#### - TO-DO
1. **Figures and tables**: Insert figures and tables into paper:  
    1. **Figure and subfigure**: Fig. 1, 3-5, 7-10; (6, 11, 12, 13)a-b  
    2. **Table**: TABLE I and II  
2. **Equations and flow-charts**: Equation 1-3; Fig. 2  

---
### Checkpoint 3
#### - Deadline: Sun., May 19, 2019
#### - TO-DO
1. **Advanced**: Might be difficult, but you should give it a try.  
    1. **Algorithms**: Algorithm 1 and 2  
    2. **line-charts**(optional): Fig. 4, 5, 7, 10, and 13 (use any data you want)(rather than use PNG files)  
2. **Layout**: Adjust your layout as close as possible to the target paper.  

## PDF in commits
1. **Put Diff PDFs in each commit**  
2. **Put Paper PDF in final commit**: use `git add -f build/Paper.pdf` before commit  

## Note
### Diff
1. **gen_diff.sh**: Make sure you can run this script; otherwise, you may not pass final project  

### Texmaker
1. **First build (4 steps)**:  Quick Build > BibTeX > Quick Build > Quick Build  
Use Quick Build (or PDFLaTeX) rather than LaTeX, or you may get compile error (e.g., inserting .png fig)  
2. **run_editor.sh**: You should use this script to run Texmaker; otherwise, you'll get file not found error  

### LaTeX
1. **Quotation marks**: `` `single quotes' `` for 'single quotes', and ``` ``double quotes'' ``` for "double quotes"  
2. **Greek letters and math symbols**: `$\mu$` for $`\mu`$, `$123 \times 456$` for $`123 \times 456`$, etc.  

## Reference
### In Folder '[ref](https://est-latex.sjf.tw/shared/latex_checkpoint/tree/master/ref)'
1. IEEE template (.tex, .pdf)  
2. Checkpoint PDF (origin, target)  

### Template
1. IEEE [template](https://www.ieee.org/conferences/publishing/templates.html)  

### Tutorials
1. [Pai](https://epl.tw/latex/)  
2. [NCTU](http://jupiter.math.nctu.edu.tw/~smchang/latex/latex123.pdf)  
3. [NTHU](http://www.cs.nthu.edu.tw/~cherung/teaching/2009cs5321/link/latex.pdf)  

