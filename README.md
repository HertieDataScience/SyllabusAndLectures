[<img src="img/HertieCollaborativeDataLogo_v1.png" align="right" height="75" width ="75"/>](http://www.hertie-school.org/)

# MPP-E1180: Introduction to Collaborative Social Science Data Analysis

### Fall 2014

**Version: *4 December 2014***

### Instructor: Christopher Gandrud

- Office: 1.42

- Email: <a href="mailto:gandrud@hertie-school.org">gandrud@hertie-school.org</a>

- Website: <a href="http://christophergandrud.blogspot.com/">http://christophergandrud.blogspot.com/</a>

- Work: <a href="https://github.com/christophergandrud">https://github.com/christophergandrud</a>

The objective of this course is to **learn how to collaboratively and reproducibly gather social data, analyse it, and effectively present results**.

**The course is intended to be immediately useful for your academic work, as well as work in the public and private sectors**. The tools you learn and the final project you complete in this course will be directly useful for your **thesis research**. As increasing emphasis in **academics** is being placed on the skills needed to effectively gather, handle, and analyse data as well as present results to a range of audiences in highly reproducible ways, this course will provide you with important tools for future academic study. **Governments** and international institutions are increasingly adopting the technologies and methods of collaborative open data science. For examples, see initiatives by the [World Bank](http://blogs.worldbank.org/opendata/open-data-community-grows-together-stays-together), [Germany](https://www.govdata.de/neues), [New York City](https://nycopendata.socrata.com/), the [United](https://gds.blog.gov.uk/2012/10/12/coding-in-the-open/) [Kingdom](https://gdstechnology.blog.gov.uk/2014/01/27/how-we-use-github/), and  the [United States](https://www.data.gov/open-gov/). These and many more resources provide great new opportunities for open evidence-based policymaking. This course is designed to enable you to take full advantage of these opportunities and actively contribute to these initiatives. Finally, the skills we will learn in this course are also widely used in **business**. R programming skills in particular are [highly valued](http://blog.revolutionanalytics.com/2014/02/r-salary-surveys.html) in fields such as finance and information technology. Being able to effectively communicate results from statistical analyses in dynamic, often web-based formats is highly valued by businesses and increasingly in governments and academics.

**A large part of the practice of social science data analysis is computer programming**. Learning how to approach the analysis of data from a computer science perspective will allow you to take full advantage of state of the art statistical tools and best practice research methods for understanding social phenomena and effectively communicating your findings in multiple mediums.

The course will involve learning the fundamentals of widely used computer languages. The statistical language [R](http://en.wikipedia.org/wiki/R_(programming_language)) will allow us to gather and analyse our data. The [Markdown](http://daringfireball.net/projects/markdown/)/[HTML](http://en.wikipedia.org/wiki/HTML) and [LaTeX](http://en.wikipedia.org/wiki/LaTeX) markup languages will allow us to present our results to a variety of audiences. We will use [Git](http://git-scm.com/)/[GitHub](https://github.com/) to version control and store all of our files. This will enable collaboration and full reproducibility.

The focus of this course is **active in class participation and collaboration** on **realistic projects** using the concepts and tools introduced in lectures and scholarly articles. All assignments and projects will be completed in teams. I encourage you to use [pair programming](http://en.wikipedia.org/wiki/Pair_programming) and even collaborate across teams.

Alongside learning the details of how to use specific tools of collaborative and reproducible social science data analysis we will emphasise their **general properties** and how they fit together into a highly collaborative and reproducible research workflow. Languages and technologies come and go, so it is important to understand the fundamental principles underlying them so that you can adapt to new technologies and understand previous researchers' work.

### Prerequisites

The course assumes that you have a good basic understanding of descriptive and introductory inferential statistics (e.g. data types, ways of describing distributions, significance testing, linear models, and so on). **Knowledge of particular software or computer programming is not assumed**.

**Patience** is a key skill for computer programming. Computer languages are extremely literal. This can lead to 'communication problems' between you and the computer. It does not share your assumptions, so you have to be very explicit. This quality makes using these tools great for recording your research steps so that they are highly reproducible. But it can also be maddening and requires patience to deal with effectively.

### Materials

**Readings**

> Gandrud, Christopher. 2013. *[Reproducible Research with R and RStudio](http://christophergandrud.github.io/RepResR-RStudio/)*. Chapman & Hall/CRC Press, Oxford. (**RRRR**)

A good reference text to have by your side when doing statistics with R is:

> Crawley, Michael J. 2005. *[Statistics: An Introduction Using R](http://www.hertie-school.org/campus/library/find-resources/ebooks/)*. John Wiley and Sons Ltd., Chichester.

A great free resource for more advanced R programming is is Hadley Wickam's aptly named [Advanced R Programming](http://adv-r.had.co.nz/). This has a lot of useful resources especially for package development.

If you ever get stuck, a good first place to turn for answers is [StackExchange](http://stackexchange.com/). If you are stuck on a coding problem, chances are someone else has had the same problem before, asked an question on StackExchange, and found answers.

**Software and Computers**

All of the software used in this course will be open source, i.e. free.

- Please bring your own laptop to class. What we do in the course requires you to have **administrator privileges on your computer**. It's preferable that you have a computer with Mac or (similarly) Linux OS. Windows is also fine, there will just be a few extra steps and it may take more time for me to help you resolve bugs.

- Sign up for a [GitHub account](www.github.com) and [install Git](https://help.github.com/articles/set-up-git).

- Install [LaTeX](http://latex-project.org/ftp.html). This is a large install, so dedicate some time to doing it.

- Download and install [R](http://cran.ma.imperial.ac.uk/) and [RStudio](http://www.rstudio.com/ide/download/).

- You need to have a modern web browser installed on your computer. [Chrome](https://support.google.com/chrome/answer/95346?hl=en) or [Firefox](http://www.mozilla.org/en-GB/firefox/new/) are the best choices for what we will do in Week 7: Automatic Data Gathering via Web Scraping.

**Lectures**

All lecture materials and their source files will be hosted in the [course's GitHub repository](https://github.com/christophergandrud/Hertie_Collab_Data_Science).

You are **highly encouraged to suggest** changes to the lecture material with a pull request (we'll learn about how to do this in Week 2) if you think of improvements that can be made for clarity, relevance, and to fix typos.

#### Assessment:

| Name                    | Percent of Final Mark | Due              |
| ----------------------- | --------------------- | ---------------- |
| Pair Assignment 1       | 10%                   | Week 3           |
| Pair Assignment 2       | 10%                   | Reading Week     |
| Pair Assignment 3       | 10%                   | Week 9           |
| Collaborative Research Project | 50%            | Presentation: Week 12, Paper/Website: Final Exam Week |
| Attendance/active Participation | 20%           | -                |

1. The **first pair assignment** is designed to develop your understanding of file structures, version control, and basic R data structures and descriptive statistics. Each pair will create a new public GitHub repository. The  repository should be fully documented, including with a descriptive README.md file. The repository will include R source code files that access at least two core R data sets, perform basic transformations on the data, and illustrate the datas' distributions using a variety relevant of descriptive statistics. At least one file must dynamically link to another in a substantively meaningful way. Finally, another pair must make a pull request and it should be discussed and merged.  **Deadline Week 3, 10% of final grade**.

2. The **second pair assignment** is a proposal for your Collaborative Research Project. It is an opportunity for you to layout your collaborative research paper question, justify why it is interesting, provide basic literature review (properly cited using BibTeX), and identify data sources/methodologies that you can access to help answer your question. You will also demonstrate your understanding of literate programming technologies.  **Deadline Reading Week, 2,000 words maximum, 10% of final grade**.

3. In the **third pair assignment** you will gather web based data from at least two sources, merge the data sets, conduct basic descriptive and inferential statistics on the data to address a relevant research question and briefly describe the results including with dynamically generated tables and figures. Students are encouraged to access data and perform statistical analyses with an eye to answering questions relevant for their Collaborative Research Project. **Deadline Week 9, the write up should be 1,500 words maximum and use literate programming, 10% of final grade**.

4. For the **Collaborative Research Project** you will pose an interesting social science question and attempt to answer it using standard academic practices including original data collection and statistical analysis. The project should be considered a ‘dry run’ for your thesis. The project has **three presentation outputs** designed to present your research to multiple audiences.  The first is a oral presentation (**10 minute maximum**) given in **Week 12**. The second is a standard academic paper (**6,000 words maximum**) that is fully reproducible and dynamically generated. The third is a website designed to present key aspects of your research in an engaging way to a general audience. The **paper and website are due in the Final Exam Week**. The presentation and website are each worth 10% of your final mark. The paper is worth 30%.

All of the assignments for the course will be completed in pairs. All assignments must be developed using Git and submitted on GitHub. All assignments, including the version history must be completely reproducible from the repository files. In general a single mark for the pair will be given. However, as all assignments are developed using Git, your contributor statistics will be taken into consideration. Major discrepancies between team members will result in scores reflecting individual’s contributions.

Assignments are due by **midnight on Friday**. When you have completed the assignment, email me the GitHub tag URL for the final version of your assignment.

**Examination Requirement**: Weighted average grade of all course assignment must be 50% or higher on numerical scale.

**Students Attendance/Participation**: Students are expected to be present and prepared for every class session. Active participation during lectures and seminar discussions is essential. Participation involves both 'traditional participation' in terms of engaging in class discussions, It also involves non-traditional participation such as pair programming and actively contributing to both your team’s projects and other team’s projects via Git pull requests. You are even encouraged to make pull requests to the main course material if you find an error or think of an improvement. As such, your GitHub contributor statistics will be used to partially evaluate your participation.

If unavoidable circumstances arise which prevent attendance or preparation, the instructor should be advised by email with as much advance notice as possible. Please note that students cannot miss more than two sessions. For further information please consult the examination rules §4.

**Late assignments**: For each day the assignment is turned in late, the grade will be reduced by 10% (e.g. 2 days after the deadline would result in 20% grade deduction).


## Part I: Motivation and getting started

### Week 1: Introduction to the Course

In this week I will give a general overview of the course objectives and key concepts. We will also make sure that you are able to install and load all of the necessary software required for the course.

#### Readings:

- Ch.1-[2](https://github.com/christophergandrud/RepResR-RStudio/raw/gh-pages/other/ReproducibleResearch_Chapter2.pdf): RRRR.

- Peng, Roger D. 2011. [''Reproducible Research in Computational Science''](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/pdf/nihms382015.pdf). *Science*. 334(6060): 1226-1227.

*Reading Extras:*

- Lazer, David, et al. 2009. ''[Computational Social Science](http://www.sciencemag.org/content/323/5915/721.summary)''. *Science*.  323(5915): 721-723. ([Open access version](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2745217/))

- Stodden, Victoria and Miguez, Sheila 2014. ''[Best Practices for Computational Science: Software Infrastructure and Environments for Reproducible and Extensible Research](http://dx.doi.org/10.5334/jors.ay)''. *Journal of Open Research Software* 2(1):e21.

- Donoho, Donald. 2010. [''An Invitation to Reproducible Computational Research''](http://biostatistics.oxfordjournals.org/content/11/3/385.short). *Biostatistics*. 11(3): 385-388.

- Herndon, Thomas, Michael Ash, and Robert Pollin. Forthcoming. [''Does High Public Debt Consistently Stifle Economic Growth? A critique of Reinhart and Rogoff''](http://cje.oxfordjournals.org/content/early/2013/12/17/cje.bet075.short). *The Cambridge Journal of Economics*.

- Lazer, David. Ryan Kennedy, Gary King, and Alessandro Vespignani. 2014. ''[The Parable of Google Flu: Traps in Big Data Analysis](http://www.sciencemag.org/content/343/6176/1203.summary)''. *Science*. 343(6176): 1203-1205.

### Week 2: Files, File Structures, Version Control, & Collaboration

Fundamentally, your research is a collection of files (preferably text files). Organising, manipulating, and storing files is at the heart of research practice. Well organised and stored files are crucial for enabling collaboration and making your research reproducible. We will learn how file systems work, as well as how to organize, version control with Git/GitHub, and store research files to enable collaboration and reproducibility.

#### Readings:

- Ch 4-5: RRRR.

- Stewart, James. 2014. [''How the GDS uses git and github''](https://gdstechnology.blog.gov.uk/2014/01/27/how-we-use-github/). *United Kingdom Government Data Service*.

*Reading Extras:*

- Use the nice [interactive introduction to Git from the Code School](http://try.github.io/levels/1/challenges/1).

- Wilson, Greg. 2014. [''Why Do Scientists Want to Learn About Code Review?''](http://mozillascience.org/why-do-scientists-want-to-learn-about-code-review/). Mozilla Science Lab.

- [Making Your Code Citable](https://guides.github.com/activities/citable-code/). 2014. GitHub Guides.

- King, Gary. 2007. "[An Introduction to the Dataverse Network as an Infrastructure for Data Sharing](http://gking.harvard.edu/files/gking/files/dvn.pdf)". *Sociological Methods and Research*. 36(2):173-199.

If you additionally want to get really good at command line file management (pretty much what the command line is best at) a great book to use is:

- Shotts Jr., William E. 2012. ''The Linux Command Line: A complete introduction''. No Starch Press, San Fransisco.

### Week 3: Introduction to the R Programming Language

We will learn the basics of the R statistical programming language for data handling and simple descriptive statistics, as well as general computer science problem solving skills.

#### Readings:

- p: 27-44: RRRR.

- Ch. 2-4: Crawley, Michael J. 2005. *Statistics: An Introduction Using R*. John Wiley and Sons Ltd., Chichester.

*Reading Extras:*

- Ch. 1: Spraul, V. Anton. 2012. *Think like a Programmer*. San Francisco: No Starch Press.

**Style Guides**: it generally doesn't matter what style guide you use for your code, but it is good to agree on a style with your team and stick to it. Otherwise it will take longer to figure out what your teammates are doing. If your teammates have difficulty understanding your code, other researchers will be even less able to figure out what you did. Two widely used style guides are:

- Wickham, Hadley. 2014. [Style Guide](http://adv-r.had.co.nz/Style.html). Advanced R Programming.

- [Google's R Style Guide](https://google-styleguide.googlecode.com/svn/trunk/Rguide.xml)

## Part II: Markup languages and literate programming

### Week 4: Introduction to Markup Languages and Literate Programming (1)

A markup language is a set of instructions that allows you to take a text file and turn it into some formatted presentation document such as a PDF or webpage. Markup languages are a crucial tool for collaborative data science for at least two reasons. First they enable literate programming--the combination of computer code and the human readable description of this code--that is the foundation of highly reproducible research. Second, data is often embedded in markup languages, especially on websites. Understanding how markup languages work will enable you to gather this data more easily.

This week we will focus on learning one of the simpler markup languages--[Markdown](http://daringfireball.net/projects/markdown/syntax) as well has how to use Markdown for literate programming with [knitr](http://yihui.name/knitr/).

#### Readings

- Section 3.3 and Ch. 13: RRRR.

- RStudio. 2014. [RMarkdown--Dynamic Documents for R](http://rmarkdown.rstudio.com/).

- RStudio. 2014. [Presentations with ioslides](http://rmarkdown.rstudio.com/ioslides_presentation_format.html).

### Week 5: Introduction to Markup Languages and Literate Programming (2)

We will expand our understanding of markup languages and literate programming by venturing into two more advanced languages: HTML and pandoc/LaTeX/BibTex.

#### Readings

- Ch. 11-12: RRRR.

- RStudio. 2014. [Pandoc Markdown](http://rmarkdown.rstudio.com/authoring_pandoc_markdown.html).

**Extras:**

Kieran, Healy. 2014. [Plain Text, Papers, Pandoc](http://kieranhealy.org/blog/archives/2014/01/23/plain-text/).

## Part III: Data gathering, transformation, & analysis

### Week 6: Automatic Data Gathering via Curl, API Packages + Cleaning

Most social science data sets are now available for download online. This week we will learn how to programmatically access this data and clean it so that it can be used for statistical analysis. We will also consider the benefits and challenges of government increasing the openness and accessibility of their data.

#### Readings

- Ch. 6-7: RRRR

- Wickham, Hadley. 2014. “[Tidy Data](http://www.jstatsoft.org/v59/i10)”. Journal of Statistical Software 59(10): 1–23.

- Janssen, Marijn, and Yannis Charalabidis, and Anneke Zulderwijk. 2012. [''Benefits, Adoption Barriers and Myths of Open Data and Open Government''](http://www.tandfonline.com/doi/abs/10.1080/10580530.2012.716740). *Information Systems Management*. 29(4): 258-268.

**Extras**

- Leeper, Thomas J. 2014. ''[Archiving Reproducible Research with R and Dataverse](http://journal.r-project.org/archive/accepted/leeper.pdf)''. *The R Journal*.

- The [World Bank's Development Indicators](http://data.worldbank.org/data-catalog/world-development-indicators), accessible through R with [WDI](https://github.com/vincentarelbundock/WDI).

- [German Government data portal](https://www.govdata.de/#)

- [Federal Reserve Economic Data](http://research.stlouisfed.org/fred2/), accessible through R with [quantmod](http://cran.r-project.org/web/packages/quantmod/quantmod.pdf).

- [rOpenGov](http://ropengov.github.io/projects/)

### Week 7: Automatic Data Gathering via Web Scraping + Transformations

A considerable amount of social science data is not stored in traditional data table type formats. Instead it is embedded in webpages. To access this data we will learn the basics of web scraping.

We will also be examining in more detail ways to transform data, particularly
with the [dplyr](http://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html) package.

#### Readings

- Wickham, Hadley. 2010. ''[stringr: modern, consistent string processing](http://journal.r-project.org/archive/2010-2/RJournal_2010-2_Wickham.pdf)''.
*The R Journal*. 2(2): 38-40.

- A key tool for scraping websites (and dealing with text in general) is [Regular Expressions](http://en.wikipedia.org/wiki/Regular_expression). You can think of these as patterns of text to search for. To prepare for class read the helpful [regular expressions overview by Greg Bacon](http://stackoverflow.com/a/2759417) and practice using them with the [RegexOne](http://regexone.com/) website.

*Reading Extras:*

- Sanchez, Gaston. [Handling and Processing Strings in R](http://gastonsanchez.com/Handling_and_Processing_Strings_in_R.pdf).

- Barberá, Pablo. 2013. "[NYU Politics Data Lab Workshop: Scraping Twitter and Web Data Using R](http://www.nyu.edu/projects/politicsdatalab/workshops/twitter.pdf)".


### Week 8: Statistical Modelling with R

We will learn how to fit and evaluate a variety of statistical models using the
R language, including simple linear models and logistic regression models for
binary dependent variables. We will also discuss basic techniques for model checking and showing
results from these models.

#### Readings:

- Ch. 7-8, 11: Crawley, Michael J. 2005. Statistics: An Introduction Using R.
John Wiley and Sons Ltd., Chichester.

*Reading Extras*

- King, Gary, Micheal Tomz, and Jason Wittenberg. 2001. [Making the Most of
Statistical Analyses: Improving interpretation and presentation](http://gking.harvard.edu/files/gking/files/making.pdf).
*American Journal of Political Science*. 22(4): 341–355.


## Part IV: Communicating results from statistical analyses

### Week 9: Automatic Table Generation and Static Visualisation

We will first learn how to automatically generate summary and results tables for multiple markup languages using  [stargazer](http://cran.r-project.org/web/packages/stargazer/stargazer.pdf). We will then learn static descriptive and inferential data visualisation best practices including avoiding introducing optical illusions that distort data presentations and accommodating readers with visual impairments. We will also cover specific R packages for creating static visualisations, primarily [ggplot2](http://docs.ggplot2.org/current/) and [ggmap](http://journal.r-project.org/archive/2013-1/kahle-wickham.pdf) for mapping.

#### Readings

- Ch. 9: RRRR.

- Ch. 1, 4, and 9: Tufte, Edward R. 2001. The Visual Display of Quantitative Information. Cheshire, Connecticut: Graphics Press.

*Reading Extras:*

- Schenker, N., & Gentleman, J. F. 2001. On Judging the Significance of Difference by Examining the Overlap Between Confidence Intervals. The American Statistician, 55(3), 182–186.

- Wickham, H., Cook, D., Hofmann, H., & Buia, A. (2010). [Graphical Inference for Infovis](http://stat.wharton.upenn.edu/~buja/PAPERS/Wickham-Cook-Hofmann-Buja-IEEE-TransVizCompGraphics_2010-Graphical%20Inference%20for%20Infovis.pdf). IEEE Transactions on Visualization and Computer Graphics, 16(6): 973–979.

- Gelman, Andrew, and Phillip N Price. 1999. ''[All Maps of Parameter Estimates Are Misleading](http://www.stat.columbia.edu/~gelman/research/published/allmaps.pdf).'' Statistics in Medicine 18: 3221–34.

- Fruehwald, Josef. 2012. [AVML 2012: ggplot2](http://www.ling.upenn.edu/~joseff/avml2012/).

- Donahue, Rafe M. J. 2011. [Fundamental Statistical Concepts in Presenting Data: Principles for Constructing Better Graphics](http://biostat.mc.vanderbilt.edu/wiki/pub/Main/RafeDonahue/fscipdpfcbg_currentversion.pdf). Version 2.11.


### Week 10: Dynamic Visualisation

The transition of publishing from static mediums such as print journals and books to internet based platforms has greatly expanded the tools data scientists have to dynamically communicate results. In particular, a number of tools frequently powered by [JavaScript](http://www.w3schools.com/js/DEFAULT.asp) make interactive presentations possible. There are a number of R based tools that allow you to use these technologies within Markdown/HTML presentation documents.

- [googleVis](https://code.google.com/p/google-motion-charts-with-r/)

- [rcharts](http://rcharts.io/)

*Reading Extras:*

- [d3.js](http://d3js.org/)

- [Shiny Server](http://shiny.rstudio.com/)

- Sigal, Mathew. 2011. [Make it Pretty: An Graphical Post-Processing with Adobe Illustrator](https://4aeb9508-a-62cb3a1a-s-sites.googlegroups.com/site/matthewsigal/teaching/Sigal-2011-Post-Processing-Handouts.pdf?attachauth=ANoY7cofvfsNzK3PAtJVKM04n5w_eMlJoFb4x2vANV6tPyiFXmb9TSCK4fKy6aKXmZPoj4hkblLr6Sdr50eliXtuN8VtIsqr5P0R4kkrZfXDzAn9nZlRdroAaIT8XVqNRuaR0Kbl90_F1HvJLuID2QkxbZv6Ft4UpkbOD1ahe94iHjSKmcKlD1hM-hjL90Nybj9WVS5DGdM-tVReWYDoI-_PtxjgYdS9lZJ3Jz5uf1CWptYE5YSzRRU1XLmPwCkD-PwzYvWtDDTT&attredirects=0). Presentation to York University Department of Psychology Quantitative Methods Brownbag.

## Part V: Collaborative research project

### Week 11: Prepare Collaborative Research Project

We will bring together all of the tools we have learned to conduct an original collaborative and reproducible research project. You will present the results from the project in multiple mediums including as a paper, a presentation to the class, and a website. The project should ideally be the starting point of your thesis. Week 11 is an opportunity for you to work on your project and ask questions/get immediate feedback from the instructor/classmates.

### Week 12: Present Results

---

[<img src="img/HertieLogoBasic.png" align="left" height="75" width ="150"/>](http://www.hertie-school.org/)

[<img src="http://media.tumblr.com/023c285c14ef01953d3b67ffe789004d/tumblr_inline_mor1uu2OOZ1qz4rgp.png" height = "100" align="right" />](http://nadrosia.tumblr.com/post/53520500877/made-in-berlin-badge-update)

<br>
<br>
<br>

Licensed under [MIT](https://raw.githubusercontent.com/christophergandrud/Hertie_Collab_Data_Science/master/LICENSE)
