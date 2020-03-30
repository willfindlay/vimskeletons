---
author: |
    | William Findlay
title: |
    | Untitled
subtitle: |
    | Untitled
date: \today
subparagraph: yes
documentclass: findlay
header-includes:
    #- \addbibresource{/path/to/bib}
classoption: 12pt
indent: true
numbersections: true
# It's annoying that I have to add this but okay pandoc...
linkcolor: black
urlcolor: blue
citecolor: Green
---
<!-- Title page -->
\maketitle
\thispagestyle{empty}

<!-- Table of contents -->
\newpage
\begingroup
\hypersetup{linkcolor=black}
\tableofcontents

<!-- List of figs, tables, listings -->
\newpage
\listoffigures
\newpage
\listoftables
\newpage
\lstlistoflistings
\endgroup

<!-- Comment this for normal spacing -->
\onehalfspacing

<!-- Setup the rest of the document -->
\newpage
\pagenumbering{arabic}
\setcounter{page}{1}






<!-- References -->
\clearpage
