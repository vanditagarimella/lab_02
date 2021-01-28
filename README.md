# STA 323 & 523: Lab 02

## Description

The lab exercises focus on Shell commands and using the Terminal in RStudio,
attributes associated with atomic vectors, and subsetting atomic vectors. Using
git from the command line is also reinforced. R Markdown is used as tool for
reproducible research. Directions are in file `lab_02.Rmd`.

## Learning objectives

- Shell commands
- Atomic vector attributes
- Subsetting atomic vectors
- Git from the command line

## Some useful git commands

|                  git Command | Description                                          |
|-----------------------------:|:-----------------------------------------------------|
|           `git clone <repo>` | Clone repo located at `<repo>` onto local machine    |
|                 `git status` | List which files are staged, unstaged, and untracked |
|                   `git diff` | Show unstaged changes                                |
|   `git add <directory/file>` | Stage changes of `<directory/file>`                  |
|  `git commit -m "<message>"` | Commit staged snapshot with a summary `<message>`    |
| `git push <remote> <branch>` | Push the `<branch>` to `<remote>`                    |

On Unix-like systems, use `man` to get help on git commands.
For example, `man git-push` will pull up the manual page for `git push`.
Windows users using git bash can use `git --help` and `git push --help`.

Also, refer to the Git cheat sheet available [here](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).
