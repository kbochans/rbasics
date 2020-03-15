# rbasics

A quick way to get familiar with the general ideas behind R.


## Your First Task

Your very first task, before you even start to learn a little R, is to become familiar with version control. Version control just means that you keep a record of every little change you make to your code so if something breaks, it is easy to fix.

One of the most popular version control systems (VCS) is called `git`. Basically you create a hidden `.git` file in a directory/folder you are working in and it keeps a record of what you change. **If** you want your code to be accessible online, you can also use the service Github. For starters, you should know these 5 commands to use `git`.

1. `git clone <repo-url>`: You only do this when you want to copy a remote repository (eg. on GitHub) to your computer.
1. `git status`: See if you made any changes.
1. `git add <file-name>` or `git add .`: Add changes you want to commit/write to a record (`.git` file).
1. `git commit -m 'add brief informative message'`: Add a note about what you did.
1. `git push`: Sync your local changes with the remote folder.
1. `git pull`: Sync remote changes with your local folder. This is important if multiple people are working on the same project.

## Your Following Tasks

Explore the following files in the suggested order.

1. [Making Life Easy with RMarkdown](example_r_markdown.Rmd)
  - RMarkdown is file that lets you write your code, takes notes and produce a nice looking output.
  
1. [The Basics of R](r_basics.Rmd) - Need to clean up a bit.
  - Learn about a variable, a vector, a function
  
1. [The Basics of Data Preparation with R](data_preparation_basics.Rmd) - Not very complete.. need data
  - Learn why you should probably use a meta-package called `Tidyverse` instead of base R. Yes I'm biased.
  - Also this is the **most** critical step of anything data. 
  - Most peoples problems are not that they can't analyze their data, its that they can't even get it into a useable format *in order to* analyze it.
  
1. [The Basics of Data Analysis with R ](data_analysis_basics.Rmd) - Not very complete
  - Some basics for describing your data and making comparisons with it.

