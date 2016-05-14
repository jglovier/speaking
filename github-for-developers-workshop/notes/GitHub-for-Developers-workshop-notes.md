# GitHub for Developers workshop (Squares Conference 2016)

## Introduction (1:30 - 2:35)
- Hi, I'm Joel Glovier; I'm @jglovier on GitHub; I'm a Sr Product Designer and I've been at GitHub for 3 years

# Notes to self
- demonstrate everything via command line
- demonstrate everything via GH Desktop app
- demonstrate everything via GitHub.com

### Notes for class
- Please follow the repository so you can get announcements about the workshop
- We're going to cover alot of info; don't worry about taking notes; i'll make the slides available in our class repo
- I also have links to several helpful resources in the README of the repository
- I'll be covering the same info in several contexts throughout the workshop, so if you don't get something at first, just hang tight and hopefully it will make more sense as we cover it again in the next section
- We will have a Q&A session at the end, so if you have questions, just post in the questions issue (#6) and I'll go through all of those at the end

## Overview of our workshop (1:35-1:40)
- An overview of GitHub • (1:40-2:00)
- GitHub Flow • (2:00-2:20)
- Collaborating with other developers • (2:20-2:30)
- A quick look at Git commands • (2:30-2:40)
- Q&A (issues/6) • (2:40-3:00)

## An overview of GitHub (1:40-2:00)

### the difference between Git and GitHub
- Git-scm.com - an open source version control system
	- all the benefits of traditional version control: 
		- versioning your work (i.e. keeping a history of your code) 
		- restoring previous versions
		- collaboration with other devs
		- backup
	- for working on parts of your project in separate areas without affecting other areas
	- different from other version control systems, Git is a Distributed Version Control System (which means you don't need a network connection; every opteration is local and very fast - except for syncing with your remote)
- GitHub.com - a private company that provides public hosting of Git repositories
	- most popular place to share Git repositories with other people
	- helpful for backing up your repositories
	- useful for collaborating on your code with other developers

### Repositories
- Repositories are where work on a given project takes place; it's like a root directory
- Go to `jglovier/github-for-developers-squares-2016` and check out the resources
	- this is a repository; repositories are the place work happens on GitHub; (see github.com/rails/rails for example, and github.com/nodejs/node)
- You can have public repositories and private repositories
	- A public repository technically speaking doesn't mean your project is licensed to be open source; it just means other people can see your project, and fork it
- There are organizations and personal accounts, and a repository can belong to either
- Every repository supports a GitHub Pages site

### Cloning
- The process of copying a repository from GitHub (the "remote server") to your local machine
- You can clone from the command line, or with GitHub Desktop

### Branches
- Your repository can have `n` branches
- The purpose of a branch is to provide a safe place to make changes to code without breaking your stable code
- Work happens on a branch, and gets merged into another branch (e.g. master) via a pull request
- GitHub Pages uses a special branch called `gh-pages` to host your code

### Making commits
- Commits are logged changes to the code
- The items that make up your project history
- You can commit from the Desktop app or the command line

### Issues
- Open an issue asking people to comment on the issue
- Issues are a feature of GitHub.com
- They are independent from your stored Git repository information
- For keeping track of tasks, planning features, and logging bugs 
- Explain markdown (show Mastering Markdown guide, and link to it in README)

### Pull Requests
- Open a pull request via web flow to edit a document
- have the class open a pull request adding their name to the workshop list
- Used to request changes from one branch be merged into another (e.g. the master branch, or any other branch)
- Pull Requests initiate discussion about your commits
	- A feature of GitHub.com, not Git
	- You can @mention other people or teams
- Useful for contributing to open source projects and for managing changes to shared repositories
- Fundamental to GitHub Flow
- Learn more at: https://guides.github.com/introduction/flow/

### Forking
- Creating an independent copy of another project
	- Useful for contributing to open source projects
	- Can be updated from “upstream”
- Useful if you want to customize a project beyond the scope of the original project (e.g. Electron is a fork of Chromium, a customized Node package, etc)
- Used just like any other repository, except it has an upstream link to another repository
- Learn more at: https://guides.github.com/activities/forking/

### Git Operations: Terminal vs GitHub Desktop
- The terminal is the default place where you operate Git
- GitHub Desktop is a GUI that abstracts some of the complexities of Git and allows you to use GitHub flow without the Terminal
- GitHub Desktop is not a full fledged Git client, so there are many Git operations which you cannot perform with GH Desktop

## GitHub Flow (2:00-2:20)
- There's lots of ways to use GitHub, but it's designed to be used with GitHub Flow
- GitHub Flow is really just putting together several of the core components we just talked about into a particular workflow

### 1. Branch

When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the master branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.

Also, it's important to note that you should almost always branch from master, so that your branch is using the latest stable code as it's foundation.

### 2. Commit

Once your branch has been created, it's time to start making changes. Whenever you add, edit, or delete a file, you're making a commit, and adding them to your branch. This process of adding commits keeps track of your progress as you work on a feature branch.

### 3. Open a pull request

You can open a Pull Request at any point during the development process: when you have little or no code but want to share some screenshots or general ideas, when you're stuck and need help or advice, or when you're ready for someone to review your work. By using GitHub's @mention system in your Pull Request message, you can ask for feedback from specific people or teams, whether they're down the hall or ten time zones away.

### 4. Discuss and review code...make more commits if needed

Once a Pull Request has been opened, the person or team reviewing your changes may have questions or comments. Perhaps the coding style doesn't match project guidelines, the change is missing unit tests, or maybe everything looks great and props are in order. Pull Requests are designed to encourage and capture this type of conversation.

You can also continue to push to your branch in light of discussion and feedback about your commits. If someone comments that you forgot to do something or if there is a bug in the code, you can fix it in your branch and push up the change. GitHub will show your new commits and any additional feedback you may receive in the unified Pull Request view.

### 5. Deploy your branch to production and test

Once your pull request has been reviewed and the branch passes your tests, you can deploy your changes to verify them in production. If your branch causes issues, you can roll it back by deploying the existing master into production.

### 6. Merge to master

Now that your changes have been verified in production, it is time to merge your code into the master branch.

Once merged, Pull Requests preserve a record of the historical changes to your code. Because they're searchable, they let anyone go back in time to understand why and how a decision was made.

## Collaborating with other developers (2:20-2:30)

### Adding collaborators
- You can add collaborators to any repository that you own
- Collaborators have push access to your project
- If you want people to collaborate with you but not have push access, you can simply make a public repository, and invite people to fork and open a pull request

### Creating an organizations and teams
- If you have a company, or want to collaborate on several projects with the same group of people, you may want to create an organization
- Teams are a way within an organization to make subsets of people with various areas of responsibility
- Use HospitalRun and GitHub examples

### Handling merge conflicts
- Eventually, when working on code with other people (and sometimes even on your own) you will run into a merge conflict
- A merge conflict occurs when more than once person or commit addresses the same line of code
- You have to manually resolve merge conflicts
- Do class example with our repo

## A quick look at Git commands (2:30-2:40)

### Basic Git commands
- git init • create a new local repository
- git clone [path] • copy a remote repository to your local machine
- git add • adds a file
- git commit -a • commit all changed files
- git push • pushes your local changes to the remote repository
- git pull • pulls changes down from remote to your local copy
- git status • shows the status of your local repository
- git checkout [branchname] • checkout an existing branch
- git checkout -b [branchname] • creates a new branch and makes it the current branch

### Some advanced Git commands
- `git stash` • stores your changes away from your branch so you can commit and push a subset, or reset your branch, etc
- `git stash pop` • re-introduces your stored changes
- `git bisect` • allows you to find where your code broke by splitting it in half
- `git revert` • allows you to undo a specific commit
- `git cherry-pick` • allows you to select commits from a branch that may have been discarded and remake the commits
- `git rebase` • allows you to replay your commits over the existing commits
- `git merge --squash` • allows you to squash all commits into one for benefit of creating a clean history
	- you can do that from the GitHub merge button now too!
- Learn more at: http://git-scm.com & StackOverflow

## Q&A (2:40-3:00)
- https://github.com/jglovier/github-for-developers-squares-conf-2016/issues/6

## Prior to class
- Create a GitHub account if you don't have one
- Go to [project URL] and browse the project a little
- Go to `jglovier/github-for-developers-squares-2016` and check out the resources
	- please watch the repository

## After class
- Ask everyone to complete the post workshop survey
- Add my keynote slides to the repository