# RSLcode
Code and data used to produce a recent publication in Remote Sensing Letters (https://doi.org/10.1080/2150704X.2016.1258126). You can download the `.Rmd` file and run this in RStudio. It will download the data and develop the analyses described in the letter, as well as compiling the `PDF` document. Please contact me if you have queries! Lex (a.comber@leeds.ac.uk)

*Geographically weighted correspondence matrices forlocalerror reporting and change analyses:  mapping the spatial distribution of errors and change*

Alexis Comber<sup>1</sup>, Chris Brunsdon<sup>2</sup>, Martin Charlton<sup>12</sup>, Paul Harris<sup>3</sup>

<sup>1</sup>School of Geography, University of Leeds, Leeds, LS2 9JT, UK Email: a.comber@leeds.ac.uk

<sup>3</sup>NUI Maynooth, Maynooth, Co Kildare, Ireland Email: {christopher.brunsdon; martin.charlton} @nuim.ie

<sup>3</sup>Rothamsted Research, North Wyke, EX20 2SB, UK Email: paul.harris@rothamsted.ac.uk

# Abstract
This letter describes and applies generic methods for generating local measures from the correspondencetable. These were developed by integrating the functionality of two existing R packages:`gwxtab` and `diffeR`. They demonstrate how spatially explicit accuracy and error measures can be generated fromlocal geographically weighted correspondence matrices, for example to compare classified and reference data (predicted and observed) for error analyses, and classes at times t_1 and t_2 for change analyses. The approaches in this letter extend earlier work that considered the measures derived from correspondence matrices in the context of generalized linear models and probability. Instead the methods computelocal, geographically weighted correspondence matrices, from which local statistic can be calculated. In this case a selection of the overall and categorical difference measures proposed by Pontius and Milones (2011) and Pontius and Santacruz (2014), as well as spatially distributed estimates of kappa coefficients, User and Producer accuracies. The discussion reflects on the use of the correspondence matrix inremote sensing research, the philosophical underpinnings oflocal rather than global approaches for modelling landscape processes and the potential for policy and scientific benefits that local approaches support.

**Key Words:** geographically weighted; accuracy and error; correspondence matrix; validation matrix; error matrix
