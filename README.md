# Git Commands used in terminal

Git Commands for Beginners

## Table of Contents

- [Introduction](#introduction)
- [Initializing Projects](#initializingprojects)
- [Moving within a folder or directory](#mov)
- [Basic Git commands to remember](#details)
- [Other Git commands for File creation and changes](#other)
- [Create a new Repo](#create)
- [Steps Used](#inspection)

## Introduction

A beginners guide to using VS Code terminal with git commands and GitHub. As we proceed, we will be adding more commands to this repo.

## Initializing Projects

| Command                                                     | Function                                   |
| ----------------------------------------------------------- | ------------------------------------------ |
| `git init`                                                  | Initialize a local Git repository          |
| `git clone ssh://git@github.com/[username]/[repo-name].git` | Create a local copy of a remote repository |

## Moving within a folder or directory

| Command                                                        | Function                              |
| -------------------------------------------------------------- | ------------------------------------- |
| `cd`                                                           | Change to root directory              |
| `cd ..`                                                        | Move one directory up                 |
| `pwd`                                                          | Display the current directory         |
| `ls`                                                           | Display Files and Folders present     |
| `press tab after writing 2 letters of the file or folder name` | Auto completes the file / folder name |

## Basic Git Commands to Remember

| Command                             | Function                                          |
| ----------------------------------- | ------------------------------------------------- |
| `git status`                        | Check status                                      |
| `git add [file-name with exension]` | Add a file to the staging area                    |
| `git add -A` / `git add .`          | Add all new and changed files to the staging area |
| `git commit -m "commit message"`    | Commit changes                                    |
| `git push` / `git push origin HEAD` | Push the change to Github                         |
| `git pull` / `git pull origin HEAD` | Pull the change locally from Github               |

## Other Git commands for File creation and changes

| Command                                   | Function                |
| ----------------------------------------- | ----------------------- |
| `mkdir [directory name]`                  | Create a folder locally |
| `touch [file name with extension]`        | Create a file           |
| `rm -r [name of the directory to remove]` | Remove a folder         |
| `rm [name of the file to remove]`         | Remove a file           |
| `mv [file1] [file2]`                      | Rename a File           |

## Create a new Repo

_Follow the demo_

## Steps Used

| Command             | Function                                 |
| ------------------- | ---------------------------------------- |
| `git log`           | View changes with its specific commit number |
| `git diff `         | Preview changes                          |

_Check: for Windows - click on `File` and go to `Preferences`_

_Check: for Mac - click on `Code` and go to `Preferences`_
