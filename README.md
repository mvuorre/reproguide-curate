# Curating Research Assets with git and R Studio

This is a repository for a git tutorial to be submitted to Advances in Methods and Practices in Psychological Science ([AMPPS](https://www.psychologicalscience.org/publications/ampps)). See [here](https://www.psychologicalscience.org/publications/ampps/ampps-submission-guidelines) for AMPPS publication guidelines.

## How to contribute

The manuscript is written in [R Markdown](http://rmarkdown.rstudio.com/) with the [papaja](https://github.com/crsh/papaja) R package. The source file is `manuscript/manuscript.Rmd` (knit to view resulting PDF.)

### References & Citations

References are in a bibfile in `references.bib`. I manage citations with a combination of [Zotero](https://www.zotero.org/), [citr](https://github.com/crsh/citr) R Studio add-in, and [Better Bib(La)Tex](https://github.com/crsh/citr#better-biblatex-integration). With these, citations are automatically formatted and added from Zotero to the `references.bib` file.

### Other materials

Lots of good stuff on the web:

- <http://www.geo.uzh.ch/microsite/reproducible_research/post/rr-rstudio-git/>
- <https://www.youtube.com/watch?v=KjLycV1IWqc>
- <https://www.youtube.com/watch?v=qcjpHFwCugE>
- <https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN>
- <https://jennybc.github.io/2014-05-12-ubc/ubc-r/session03_git.html>
- <http://r-bio.github.io/intro-git-rstudio/>
- <http://kbroman.org/github_tutorial/pages/rstudio.html>

# Topics (roadmap)

We plan to cover broadly these topics in roughly this order:

- Introduction
    - Reproducibility: What and how
    - git: What problem does it solve and how
    - git: microscopic history and overview, alternatives
- Organizing a project for reproducibility
    - Small example project, contrast to messy one
- git for curating materials
    - Walkthrough of important commands, create & commit README
    - R Studio IDE as git interface
- GitHub for organizing materials across time and space
- Possible other topics to include:
    - GitHub? Collaborating?
