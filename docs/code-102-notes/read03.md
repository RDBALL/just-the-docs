---
layout: default
title: Code 102 | Read 03
parent: Code 102 Notes
nav_order: 4
---

# Read: 03 Revisions and the Cloud

### Terms:
> Version Control System (VCS)  
> Local VCS (LVCS)  
> Centralized VCS (CVCS)  
> Distributed VCS (DVCS)  

### Vocab:
> Snapshot - creates save points when a repo change is committed   
> Committed - Data is securely stored in a local database  
> Modified - File has been changed but not committed to the database  
> Staged - Flagged a file’s changed version to be committed in the next snapshot  
> Cloning - Making a copy of an existing git repository from a particular server  
> Working Directory - Repo files reside here  
> Index - The area used for staging  
> Head - Points to the most recent commit  

Git is a version control system that lets multiple developers work on the same code while maintaining a history of changes to your files.

GitHub **is not** git. It is essentially an area where “git’s” are consolidated

### Notes on GIT:

What is Version Control?
Version control allows you to re-visit various versions of a file or set of files. Think of this as a save point in a game that you can come back to. Version control also tracks who made what modifications and will help compare changes. 

**A LVCS is where one fileset or database is stored locally on your system.** 

**A CVCS is stored remotely on one server and enables access by multiple developers. A CVCS will give the team a better shared understanding regarding any changes made to the files or database.**

**A DCVS, like the name implies, allows clients to create mirrored repositories to act as safeguards against catastrophic losses or crashes.**

**Git is a DVCS**

**Snapshots** create save points when a repo change is committed 

- Work is done locally to remove the need of fetching information from a server

- Changes are tracked for every commit

- Difficult for data to be truly lost

### **Snapshot process example:**
> Add - git add class1.md class2.md / or git add .  | This adds files to be included in the snapshot  


> Commit - git commit -m "message to be added to commit"  | This will stage files and add a commit message    


> Push - git push origin main  | This pushes the staged snapshot to the repo  

## Setting up Git through the terminal

Verify that your information is correct when running the command

`git config –list`

This should return your GitHub username, email and some other information. 

If you need help run the following command

`git command –help`

### Setting up a Git Repository

Cloning

Using terminal, paste in the desired repository URL

`git clone https://github.com/your_repository`

This will create a directory named after the title of your repository with a .git directory inside of it along with copies of all versions of that repo’s files.

You can add a space and a new directory name to have the cloned repo be established in the new directory

`git clone https://github.com/your_repository newdirectory`

Changes can be committed by clicking the GitHub extension on VSCode if you have the GitHub extension installed.
