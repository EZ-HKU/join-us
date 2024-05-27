# Git
If you are working on a project with multiple people, you need a version control system. Git is a distributed version control system that allows you to track changes in your codebase. It is widely used in the software development industry.
## Install
### Ubuntu
```bash
sudo apt-get install git
```
### Windows
Download and install from [git-scm.com](https://git-scm.com/)
## Setup
Before you start using git, you need to set up your name and email address.
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"
```
## Create a Repository
To create a new git repository, run `git init` in the directory you want to track.
```bash
git init
```
## Clone a Repository
To clone an existing git repository, run `git clone` followed by the repository URL.
```bash
git clone https://github.com/someuser/somerepo.git
```
## Add Files
When you create a new file or modify an existing file, you need to add it to the staging area.
```bash
git add filename
```
When there are multiple files, you can add all of them at once.
```bash
git add .
```
## Commit Changes
After adding files to the staging area, you need to commit them to the repository.
```bash
git commit -m "Your commit message"
```
## Push Changes
To push your changes to the remote repository, run `git push`.
```bash
git push
```
## Pull Changes
To pull changes from the remote repository, run `git pull`.
```bash
git pull
```