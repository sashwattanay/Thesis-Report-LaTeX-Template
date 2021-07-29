# Thesis-Report-Template

This is a LaTeX template for lengthy reports, thesis, dissertations, lecture notes, etc. 

Complilation has to be done from "main.tex"

It is very modular in structure, i.e. each chapter has a separate source file. The separate source file have cross referencing enabled (with hyperlinks).

Also, there is no issue of label clash (while referencing) between two different source files. For example, see the first equations in chapters 1 and 2 each. They have the same label "a". But there is no clash due to the use of 

\externaldocument[C1-]{chap1}
\externaldocument[C2-]{chap2}

in "main.tex".
