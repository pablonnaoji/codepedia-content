---
Title: "What is Git?"
Subjects:
  - "Web Development"
  - "Developer Tools"
Tags:
  - "Version Control" 
  - "Developer Tools"
  - "Git"
Catalog Content:  
  - "https://www.codecademy.com/learn/learn-git"
  - "https://www.codecademy.com/learn/paths/web-development"
---

Git is a version control system that allows a developer to track changes made to files in their projects. Teams of developers can use Git to collaborate on a single project at scale. This is made possible by branching, which allows developers to make specific changes to eventually be merged into the `main` branch of the codebase (or Git repository).

At it's core, Git is a command line tool that comes with built-in commands for performing a variety of tasks. 

### Common Commands with Examples

#### `git --version`

Run this command to see version running on local machine. 

```
$ git --version
git version 2.26.0
```

#### `git init`

This command initializes a new Git repository or reinitializes one that already exists.

```
$ git init
Initialized empty Git repository in /Path/to/current/working/directory/.git/
```

#### `git branch`

This command has a few applications. Some of its main functions include: 

* Listing all branches in the repository

```
$ git branch
 * branch-1
 * branch-2
 * main
```

* Creating a new branch with a specified name

```
$ git branch branch-3
$ git branch
 * branch-1
 * branch-2
 * branch-3
 * main
```

* Deleting a specific branch

```
$ git branch -d branch-2
Deleted branch branch-2 (was 670d2ed).
$ git branch
 * branch-1
 * branch-3
 * main
```


