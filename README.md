# Thesis-Report-LaTeX-Template

This is a LaTeX template for lengthy reports, thesis, dissertations, lecture notes, etc. 

Complilation has to be done from "main.tex"

It is very modular in structure, i.e. each chapter has a separate source file. The separate source file have cross referencing enabled (with hyperlinks).

Also, any clash of labels being multiply defined in different source files can be easily spotted and resolved. While compiling "main.tex", look for any warning for multiply defined labels (label clash). If there is one across different source files, then resolve it the way it's done in this template. For example, see the first equations in chapters 1 and 2 each. They have the same label "a". But there is no clash due to the use of lines

"\externaldocument[C1-]{chap1}

\externaldocument[C2-]{chap2}"

in "main.tex".
