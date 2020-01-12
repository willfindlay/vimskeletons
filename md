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
numbersections: true
# It's annoying that I have to add this but okay pandoc...
linkcolor: black
urlcolor: blue
citecolor: green
---
<!-- Title page -->
\maketitle
\thispagestyle{empty}

<!-- Comment this for normal spacing -->
\onehalfspacing

<!-- Table of contents -->
\newpage
\pagenumbering{roman}
\tableofcontents

<!-- List of figs, tables, listings -->
\newpage
\listoffigures
\newpage
\listoftables
\newpage
\lstlistoflistings

<!-- Setup the rest of the document -->
\newpage
\pagenumbering{arabic}
\setcounter{page}{1}






<!-- References -->
\clearpage
