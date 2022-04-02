# Biostatistics for Clinical Research
## Theory & Applications in R

A book in development for the Biostatistics sequence of courses (1 & 2) at the University of Jamestown PhD in Clinical Research program. The book teaches and utilizes examples with the open source computational platform R  ( https://cran.r-project.org/). There is an emphasis and equal distribution of theory and application through all chapters. There is an underlying emphasis on performing all applications utilizing reproducible research approaches (programming with sufficient commentary) and tools (GitHub, Figshare, Open Science Framework, etc) throughout the book.

## Tentative ToC

### Part One (Biostatistics I)

1. The role of biostatistics in clinical research
2. Programming Concepts in R
3. Probability & Statistical Inference
4. Measurement
5. Tidying for Tidy Data
6. Transforming for Transformed Data
7. Descriptive Statistics
8. Exploratory Analysis

### Part Two (Biostatistics II)

1. Computational Approaches to Statistical Inference
2. Methods for Statistical Modeling
3. Building Statistical Models
4. Evaluating & Interpreting Statistical Models
5. Presentation & Dissemination


## Scrivener - Rstudio - Bookdown workflow

This version has been written in Scrivener, exported as plain text as a single index.Rmd file and then used to build the book. If this worked, then it’s an entirely new workflow for writing and self publishing books that takes advantage of the organizing and writing features of Scrivener, and the computational analysis and publishing features of R, Rmarkdown and Bookdown.

At this point I’ve created a special compile format in Scrivener that puts an empty line between each folder and file. Each folder functions as a “Part” of the book, and each text file (in Scrivener) as a chapter in that part. However, Scrivener compiles one Index file which may make editorial contributions more challenging since the entire book is in one large file on Github and in bookdown. But that is something I’m willing to live with since the benefits of organizing, creating and writing in Scrivener for the project are well worthwhile.

## Bookdown format

The bookdown format allows for the book to be shared while being developed and utilized in courses with minimal hassle and lots of end user options for reading. It is also easier to work with than a learning management system for interactive course assignments and activities. The book is based on the "minimal example" of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

