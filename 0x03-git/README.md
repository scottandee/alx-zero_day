# 0x03 - Git
Git is a version control system that helps in the efficient management of small scale to large scale projects. It helps developers to log changes to code, and
collaborate with other developers. Git is a command line tool that is linked with **Github**. Github is simply a web-based service for git repositories.

## What is Git
1. Git is a version control system designed to track changes to files
2. It's a command-line tool that allows developers to create repos, commit changes, create branches, merge changes and more
3. Git operates locally on a developers machine allowing it to work offline

## What is Github
1. This is a web based hosting platform for git repos
2. Github provides more tools for managing code to developers. Tools like pull requests, code review, project management etc
3. Github serves a remote  server where repositories created in gi can be pushed to github for the whole world to see
4. Github enhances collaboration because it brings about a means foor developers to d=share their code to one another

## What is the difference between Git and Github
Git is the underlying version control system for managing code. Github is the web-hosting platform for Git. Git can exist without Github but GitHub cant exist without
Git.

## Git Cheatsheet
Here's a [git cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet/) for remembering the commands

## The Github Workflow
This is the workflow we follow when we need to add a new feature to our project
<p align="center">
  <img src="https://githubtraining.github.io/training-manual/img/github-workflow.png"  width="60%" height="30%" align="center">
</p>

* Create an new branch
* Write code for new feature and commit the changes
* Create a pull request
* Merge changes back to main branch

## Working Locally
When you work locally, your files exist in four different forms
1. Untracked: This is a file that has never been committed
2. Modified: This is a file that has been committed but has just recently been edited
3. Staged: This is a file that has been added to the staging area with the `git add` command
4. Committed: This is a file that has already been committed with the `git commit` command

We have the:
* Working area: consists of untracked and modified files
* Staging area: consits of staged files
* History: consists of committed files

## Resources
* Github training Manual [here](https://githubtraining.github.io/training-manual/#/)

## Author
* Olayinkascott Andee (andeeolayinkascott@gmail.com)
