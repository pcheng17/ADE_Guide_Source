# UCLA Applied Differential Equations Solutions Guide

All the source LaTeX files of the solutions to the UCLA ADE qualifying exams from Spring 2007 to Spring 2015. Also included are scanned copies (in PDF format) of Zane Li's hand-written solutions of Fall 1999 to Fall 2006. This basically covers all of the past qualifying exams that have been made available on the UCLA website minus a very (very very) small handful of problems. 

Original authors: [Peter Cheng](http://www.math.ucla.edu/~pcheng17), [Zane Li](http://www.math.ucla.edu/~zkli)

Contributors: 

## How this works

The PDF of the typed solutions is generated by compiling ADE_Guide.tex, which includes (via the `\input{...}` command) all other TeX files found in directory Source. 

## How to contribute 

Remember to create/work on your own branch before merging with the master branch! Here are a few guidelines to keep everything more-or-less uniform:

* One file for one exam.
* preamble.tex contains a ton of shortcuts for LaTeX commands. It's not commented well, but please feel free to add to it for your own convenience.
* Your solution TeX file name should be the first letter (capitalized) of the quarter followed the last two digits of the year (F14 = Fall 2014). This doesn't matter for compiling, but at least it keeps the directory sorted! 
* Within a solution file, each problem's solution begins with `\subsection*{Solution to ...}`, and if there are sub-problems, then each sub-problem's solution begins with `\subsubsection*{Solution to ...}`.
* You might notice that some solution TeX files have labels for each problem - this is not necessary.
* Including your solution TeX file into solution guide is super easy. Just look at ADE_Guide.tex and you'll see the pattern.

Most importantly, please add your name to the list of contributors in this README above and to acknowledge.tex! 