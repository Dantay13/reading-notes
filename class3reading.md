# Git Tutorial: A Comprehensive Guide

## Version Control 
It is a system that allows you to record changes and go back to previous versions of a file. It also allows you to track the changes, see who made the changes and compare changes. A **VCR (Version Control System)** allows you to rectify changes easier. 

### Local Version Control 
A local version control entails one database on your hard disk that stores changes to files. 

### Centralized Version Control (CVCS)
This system is a single server storing all changes and file versions, which can be accesed by various clients. This makes collaboration better by eliminating the need to involve all local databases. Programmers will have more knowledge of team members' activities and provide more control over sharing tasks. 

### Distributed Version Control (DVCS)
This addresses the vulnerability of the CVS failing. If a CVS gooes down, collaborator cannot work with each other on a file or save changes and new versions. And if there is no backup there is a possibility of losing all of the work. But the DVCS prevent this situation by allowing clients to create mirrored repositories. This serve as a data backup and can be placed on the server to replace any lost information.

## What is Git 
I is a DVCS that allow us to take snapshots of what we do to our files and folders. Each time we save (commit changes, Git creaaes a snapshot of he file and store a reference (message) to it.
<br> Files in Git can reside in three main states:
1. Commited: Data is securely stored in a local database
2. Modified: File has been changed but not committed to the database 
3. Staged: Flagged a file's changed version to be committed in the next snapshot

## Setting Up a Repository
[Link to How to Set Up a Repository in Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## ACP Process (Add, Commit, Push) 
- (A): `git add` (file name)
- (C): `git commit -m "your message"`
- (P): `git push origin main`

<br> note: to know the current status: `git status`
