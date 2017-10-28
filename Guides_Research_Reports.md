#Guides for Research Report


[TOC]

-----

##General Idea


Well organized reporting is important to your research activities. It helps both your own working progress and the collaborations.

**Note**: A report is **NOT a one time deal**; we will revisit, revise, and enrich it in the process of the research. Under version control, this setup is different from our previous practice of weekly reporting emails.

> **The purposes are:**
>
> - It helps you to plan and organize your work.
> - Writing helps you to think.
> - Good reports are readily the materials for your final project report / thesis / paper publication.
> - It shares the results, problems, ideas, etc. with your advisor and in potential collaborations. 

---

##How to compose a report

###Organization of reports

- Use descriptive titles. Each report dedicate to one aspect of a study. Keep updating on the same report for any progress on the same study. Do NOT organize report by timing (e.g., even though you update reports frequently, do not index report files by weeks.)


###Report Content

> **Report should include these components:**
>
> - **Associations**: Code and data files associated with the report.
> - **Description** of the work: How the work was done.
> - **Results**: What are the results and findings? Specify associated files / folders if any. For **evidence based** conclusions, clarify which results (specifically which figures, tables, math proofs, or derivations) led you to your conclusion. For **conjectures**, clarify that they are conjunctions, and if important, please provide ideas / plans to verify them.
> - **Thoughts**: Summary what you learned from the results and your thoughts. 
> - **Problems**: Potential problems or questions.
> - **Plan**: What to do next.
> - Other notes as appropriate.

**Note:** Please include all components into the report even if some of them do not apply at the beginning.


###Principles of writing:

- Both writing and results should be concise and organized. File / folder names of the reports and results should be concisely descriptive. It is often needed to revise the writing a few times to make sure it gets the information cross accurately and effectively, and again, is concise.

-  Try the best to visualize results by graphs, which shall company with index, title, and legend.

- Tables should also company with index, title, and legend.

- For math derivation, do not "jump" steps. Instead, try to give as many details as possible.

- For computation or data analysis, report should company with codes.

- Always document your codes and processing pipelines carefully. Write clear log/readme files as necessary providing information on sources,  processes, etc.

---

## File Format

For documentation, the following tools are recommended instead of Word. They are neater, more portable, and easier to track changes under version control (e.g., by **Git**, see the following).

#### <i class="icon-file"></i> LaTex

If you use Mac, **Texshop** (an OS X built-in app) is a great choice.

#### <i class="icon-file"></i> Markdown

- Here is information on [**Markdown**][2].
- My preferred editor for *md* files is now [**MacDown**](http://macdown.uranusjr.com/features/), which allows LaTex syntax and easy to use. I also used [**Atom**](https://atom.io), [**StackEdit**][3], and **RStudio**. Feel free to explore other choices. A list of editors for OS X can be found [here](http://www.slant.co/topics/899/~markdown-editor-for-os-x).
- **Markdown** combines with **R**: [**R Markdown**][5].

For tables, maybe Excel is still the top choice, if though version control cannot track changes in details.


---

##Management of reports


We manage reports by version control tool **GitHub** in *WPI-Wulab*'s **private** project repositories.

Please frequently sync your updates to the GitHub repositories. Inform the advisor (and other collaborators if any) the update in reasonable time before the regular discussion meeting.

For documents that do not demand frequent change and version control, they can be saved in other cloud serves, such as <i class="icon-provider-gdrive"></i> Google Drive
and <i class="icon-provider-dropbox"></i> Dropbox.

----

##Reference


- [Markdown writing and formatting syntax for GitHub.](https://help.github.com/categories/writing-on-github/)

- [Use LaTex to report and track the versions.][1]

- [Collaborating with LaTeX and git.][4] Follow the instruction to make Git only tracking the .tex files in your report.

- [Using Git with RStudio.][6] RStudio is a good editor for R-Markdown, and can also provide partial functions for dealing with Git/GitHub and editing Markdown files.

----


  [1]: http://stackoverflow.com/questions/6188780/git-latex-workflow
  [2]: http://daringfireball.net/projects/markdown/syntax "Markdown"
  [3]: https://stackedit.io
  [4]: https://www.sharelatex.com/blog/2012/10/16/collaborating-with-latex-and-git.html
  [5]: http://rmarkdown.rstudio.com
  [6]: https://jennybc.github.io/2014-05-12-ubc/ubc-r/session03_git.html#learngit
