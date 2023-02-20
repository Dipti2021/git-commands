# Git

Git Commands for Beginners

## Table of Contents

- [Introduction](#introduction)
- [Initializing Projects](#api)
- [Moving within a folder or directory](#apis)
- [Basic Git commands to remember](#details)
- [Other Git commands for File creation and changes](#other)
- [Inspection](#insp)

## Introduction

A beginners guide to using VS Code terminal with git commands and GitHub. As we proceed, we will be adding more commands to this repo.

--

### Initializing Projects

| Command                                                           | Description                                |
| ----------------------------------------------------------------- | ------------------------------------------ |
| `git init`                                                        | Initialize a local Git repository          |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

## Moving within a folder or directory

| Command                                                        | Description                           |
| -------------------------------------------------------------- | ------------------------------------- |
| `cd`                                                           | Change to root directory              |
| `cd ..`                                                        | Move one directory up                 |
| `pwd`                                                          | Display the current directory         |
| `ls`                                                           | Display Files and Folders present     |
| `press tab after writing 2 letters of the file or folder name` | Auto completes the file / folder name |

## Basic Git Commands to Remember

| Command                            | Description                                       |
| ---------------------------------- | ------------------------------------------------- |
| `git status`                       | Check status                                      |
| `git add [file-name.txt]`          | Add a file to the staging area                    |
| `git add -A`                       | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes                                    |

## Other Git commands for File creation and changes

| Command                                       | Description               |
| --------------------------------------------- | ------------------------- |
| `mkdir [directory name]`                      | Create a folder locally   |
| `touch [file name with extension]`            | Create a file             |
| `git rm -r [name of the directory to remove]` | Remove a folder           |
| `git rm [name of the file to remove]`         | Remove a file (or folder) |
| `git cp [file1] [file2]`                      | Copy a file               |
| `git mv [file1] [file2]`                      | Rename a File             |

## Inspection

| Command             | Description             |
| ------------------- | ----------------------- |
| `git log`           | View changes            |
| `git log --summary` | View changes (detailed) |
| `git diff `         | Preview changes         |

_Check: for Windows - click on `File` and go to `Preferences`_

_Check: for Mac - click on `Code` and go to `Preferences`_
