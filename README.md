---
editor_options: 
  markdown: 
    wrap: 80
---

# Guimarães' Lab GitHub

This repository was created with the intention of organizing some of the
resources used by multiple members of the Guimarães lab, collaborators, and
other researchers that might be interested. These include tutorials targeted at
learning different skills, code containing functions that are useful for
multiple members, and data sets shared by multiple lab members.

If is your first time using Git, here are some good resources that you should
check first:

-   [Quick Start for
    RStudio](https://code.publichealthscotland.scot/git-guide/quick-start-rstudio.html)
-   [Let's Git started](https://happygitwithr.com/)

## Table of Contents

The repository is organized in three main folders, they are:

-   `Tutorials/`

-   `Code/`

-   `Data/`

### Tutorials

Inside `Tutorials/`, the following files are included:

#### Coevolution in mutualistic networks *by Lucas P. Medeiros*

This excellent tutorial was created by Lucas (2018), in which he went he
introduces an R implementation of a theoretical approach to study coevolution in
species-rich interactions. Currently, the tutorial is in a markdown format in
his own
[website](https://lucaspdmedeiros.com/coevo_mut_net_tutorial/tutorial.html).

#### Maps in R with the SF package

`Maps_Sfpackage.Rmd` is a tutorial created by Augusto (2026), based on a
tutorial by [Luis D. V. Arregoitia](https://luisdva.github.io/rstats/richness/),
with some modifications and explorations that might apply to our work.

### Code

Inside `Code/`, the following files are included:

### Data

Inside `Data/`, raw data sets being used by multiple lab members are deposited.
These files are not supposed to be updated regularly, download and use them on
your own machine.

The data sets are:

## How to use and best practices

Clone this repository in your own computer. If you are adapting or modifying
code, make sure to work on your own branch and if you have any bug fixes you can
make a pull request.

When working with the data set, make sure to **always keep the raw data
intact**. Any procedures done to clean and process the data should generate a
new file. That way, all users have access to the same raw data set.

**All changes must be made on a branch — direct commits to `main` are
disabled.** Only approved pull requests, reviewed by a maintainer/mod, can be
merged into `main`.

1.  **Create a branch**

``` bash
   git checkout -b feature/your-feature-name
```

2.  **Make your changes** and commit them

``` bash
   git add .
   git commit -m "Add your descriptive message here"
```

3.  **Push the branch**

``` bash
   git push origin feature/your-feature-name
```

4.  **Open a Pull Request** on GitHub, describing what you changed and why.
5.  **Wait for approval** — a project maintainer must review and approve the PR
    before it can be merged into `main`.
