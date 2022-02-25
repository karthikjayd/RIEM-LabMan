# Compiling the record

## The main TeX file

The record can be compiled using the `record-main.tex` file.
All experiments are maintained in separate `.tex` files within
the `Experiments/` sub-folder.   

It is advisable to compress the entire folder into a `.zip` file
and upload it to Overleaf to work on the document, since this
record depends on many extra Latex packages.
(If you have installed the complete TeXLive or MikTeX installation, this wouldn't be a problem.)

# Working on Each Experiment

- The `.tex` files of the experiments to be added in the record should be included in the `Experiments/` subfolder. 
- DO NOT include any `\documentclass{}` command for the 
`.tex` files of the experiments. 
- After edits, the `record-main.tex` file is to be compiled, NOT the experiment's `.tex` file.

## Displaying the Date of Experiment

In each experiment's `.tex` file, the date of the experiment needs to be mentioned in 
three places:

`\lhead{Date: --/--/20--}` - To display the date of the experiment in the header
of pages.

`\dateofexp{Date of Experiment: --/--/20--}` - To display the date of the experiment in the Table of Contents.


```
\begin{center}
    Date of Experiment: --/--/20--
\end{center}
```
To display the date of the experiment in title page of the experiment.

## Graphs

The graphs are plotted using the `pgfplots` package in Latex, 
in the `tikzpicture` environment.

## Acknowledgement
We extend our sincere gratitude to *Dr. Santosh Kumar*, In-Charge, Physics section, DESM, RIE Mysore, for granting us this opportunity to prepare the lab record in LaTeX. 
This was a wonderful learning experience for all the contributors.

Many of the portions in the *Theory* section of the experiments have been adapted from the manuals prepared by Prof. K S Mallesh. 

This record is inspired from the works of *Dr. Niranjana K M*,
who had prepared a comprehensive lab manual for the fourth semester (Optics) laboratory sessions at RIE Mysore during the 2015-16 academic year.

## Contributors
The following students of M.Sc.Ed.Physics 2015-2021, RIE Mysore are the contributors to this laboratory record.
1. A Asoni
2. Carolin V B
3. Emmanuel Bency
4. Gayathri Raveendran
5. Gobinda Chandra Hansdah
6. Karthik J
7. Navya Jose
8. Priyabrata Majhi
9. Rabini Mariam Abraham
10. Rajib Kumar Sahoo
11. Shirisha G V
12. Subham Saswat Sahoo
13. Bharath Kumar J
14. Preeti Priya Mohanty

#### Author of sem12-lab-record.sty
Karthik J, M.Sc.Ed.Physics (2015-21), RIE Mysore

`karthikjayd@gmail.com`
