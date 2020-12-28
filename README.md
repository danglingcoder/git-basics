# Understanding Git

## What is version control?

Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

## What is git?

Git is a version control software. It is a mature, actively maintained open source project originally developed in 2005 by Linus Torvalds, the famous creator of the Linux operating system kernel. A staggering number of software projects rely on Git for version control, including commercial projects as well as open source.

## Basic Git Commands

A) Setting up your identity:

Configure the author name and email address to be used with your commits.
Note that Git strips some characters (for example trailing periods) from user.name.

```
git config --global user.name "Sam Smith"
git config --global user.email sam@example.com
```

Git is an example of a DVCS (hence Distributed Version Control System). Rather than have only one single place for the full version history of the software as is common in once-popular version control systems like CVS or Subversion (also known as SVN), in Git, every developer's working copy of the code is also a repository that can contain the full history of all changes.

## How Git works?

Git stores projects in repositories. Commits are made to the project and they tell Git that you are satisfied with the new or changed code you created.
New code/changes are committed on branches. Most of the work is committed on other branches and then merged with the master branch. All this is stored in the same directory as the project but in a sub-folder called .git.
To share the code with your colleagues you push the changes to the repository. To get the new code from your colleagues, you pull changes from the repository.
