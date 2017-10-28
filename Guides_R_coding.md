Guides for R Coding 
===================

[TOC]

-----

General Idea
-------------

We shall follow rules and best practices from professional software development to develop our computation programs. These strategic rules are necessary for efficiently and productively tackle complex problems in long term. Same ideas apply to programming R and other languages. 

> **Strategy:**
> 
> - Build libraries of functional modules that can be reused. 
> - Build libraries of work-flow controlling-functions to realize pipelines of automatic processing, analysis, visualization, and reporting.
> - Separate library development for general purposes (which is stored in the library repository) from coding of specific analysis or experimental processes (which is stored in corresponding project repositories).
> - Mature functional modules shall convert to CRAN packages. 
> - All members collaboratively contribute to libraries, and also benefit from them. (The benefit includes potential joint work and publications.) 

---

Practices 
-------------

> **Practices of R programming: **
>
> - For coding rules please refer to [Google R Style Guide][1]. 
> - Version control, source control, documentation, a project plan, scope document, bug tracking/change control, etc.
> - ALWAYS do a version control check in right before running results that go out to others, which will assure you know the EXACT state of the code when you produced those results.
> - Debugging is key for high quality functions. Carefully test the performance especially for the boundary values of the allowed range of the function parameters. 

---

Examples of library modules 
-------------
**Note:** These could be continuously revised along the development. 

- Data processing: Functions for data cleaning, quality controlling, converting raw data into desired data format, interface with database, etc. 

- Tests: Functions for calculating test statistics.

- Simulation: Functions for generating simulation data.

- Permutation: Functions for generating permutation results. 

- Visualization: Functions for visualizing data and results by graphs. 

- Calculation : Functions for numerical calculations of distribution (p-value, power), sample size, and other meaningful measurements.

-	Pipelines: Functions that wrap up other R functions to realize workflows. 

R function writing requirements 
-------------
> **Commenting all functions: ** 
>
> - *Description*: The purpose of the function. 
> - *Arguments*: Input options. Specify the requirements whenever available.
> - *Value*: Output of the function.
> - *Author(s)*: Who wrote the function. 
> - *Details*: Detailed explanation regarding the requirements, the method of realizing the function, etc. 
> - *Note*: Other potential notes and comments. 
> - *Depends on*: R libraries and/or functions on which this function depends. 
> - *Reference(s)*: Related literature such as papers, resources, etc.
> - *See Also*: Other related R functions. 
> - *Examples*: Sample R codes for applying this function. It is easy to put (part of) your codes for testing this function. **Surely all functions shall be tested carefully!**


**Note:** The above comments are for readability and for generating CRAN help files. Therefore, always keep these components even if some of them could be empty at the beginning (but could be filled in later). 

> **Principles of good R functions** 
>
> - Function is carefully tested and free of bugs. 
> - The heading comments mentioned above are well written and easy to understand. 
> - Internal coding are also well commented. 
> - A good function name should have balance between its length and precise descriptiveness about its purpose. 
> - Balance among flexibility, extendibility, and conciseness (not too long). 
> - Computation is efficient. 


> **Principles of good R coding for specific experimental processes** 
>
> - Well commented. 
> - Concise (major coding should have been taken by functions). 
> - Explicitly define parameters including the paths, such that the process can be easily repeated on different PCs and servers. 

-------


Tools:
--------------------

- Incorporate writing with reproducible R codes: **Sweave** or **knitr**.

- Create dynamic documents, presentations, and reports from R: [**R Markdown**][3].

---------

References:
--------------------

- [Guidelines and practices on R programming][2]. 

---------

  [1]: https://google.github.io/styleguide/Rguide.xml 
  [2]: http://www.r-statistics.com/tag/code-management/
  [3]: http://rmarkdown.rstudio.com  
<!--  [4]: 
  [5]: 
  [6]: 
  [7]: 
  [8]: -->
  
 