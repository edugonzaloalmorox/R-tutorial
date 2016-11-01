---
title: "A gentle introduction to R"
author: "Edu Gonzalo Almorox"
date: "10/20/2016"
output: 
 slidy_presentation: 
   font_adjustment: +2
---



## R in a nutshell 

- What is [R](https://www.r-project.org)?   _programming language_, _environment_, _software_...

    - Object programming 
    - Open source and free
    - Active community
    - Important learning curve 
    - Documentation far from perfect but getting into shape.
      
    
- What is [RStudio](https://www.rstudio.com)? Integrated Development environment that makes R programming more user friendly. 

- What can you do with R?

    - Data analysis
    - Data manipulation
    - Data visualisation
    - Dynamic documents 
      - .... possibly more things that I don´t know



## Let´s get our head around...

**Step 1: Set a project**

- Set a project

    - Organization of the files
    - Keep a better control of the workflow (e.g. scripts, data, final documents, etc...)
    - Time savings

- Generate a project 

    - `Project - New Project - New Directory -  Empty project - (select directory...)`
    - Create different folders containing different types (data, code, figures, documents...)   

- _Optional_ (although highly recomended): Create a control version of the project 

    - It prevents accidents
    - It enhances reproducibility and collaboration
    - Reduces errors 
    - Keeps record
    - Limits software dependency
    - Good tool for keeping a control if dealing with big projects

**Step 2: Resources**

- In case of doubt there are different ways to proceed: 

     - Specialised websites - e.g. [stackoverflow.com](http://stackoverflow.com/questions/tagged/r)
     - [R Mailing lists](https://www.r-project.org/mail.html)
     - `help`, `help.search()`, `??(name package/name function)`
     


## Data structures 

- In R every element is regarded as an object. Objects are data structures that group data according to specific attributes. Most general data structures are organised by two elements

    - Dimensionality (1d, 2d, 3d)
    - Type of the contents (homogeneous, heterogeneous)
    

