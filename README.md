# GIT

GIT is the stove in a software developer's kitchen. Any professional developer must know how to use it! It is an open source program for tracking changes in text files. It is used to store the source code for a project and to track the complete history of all changes made to the code. GIT's features allow developers to collaborate more effectively on projects. Importantly, it provides tools for managing possibly conflicting changes from multiple developers.

## GITHUB

GITHUB is a social and user interface for software developers built around its core technology, GIT. It is a web-based version-control and collaboration platform specifically made for developers.

## Repository

A repository is like a folder or storage space for a GIT project. A project's repository contains all of its files, such as code, documentation, images, and more. It also tracks every change that a developer (or his/her collaborators) make to each file, so the developer can always go back to previous versions of the project to fix any mistakes. In summary, a repository is a collection of commits, branches, and tags to identify commits.

## Clone

A clone is a copy of a repository that does not live on a website's server, but rather on a computer. The term can also be used as a verb to mean the act of making that copy. Clones can be useful when a developer wants to edit files in his/her preferred editor (without having to be online), but still wants to use Git to keep track of the changes. The clone is still connected to the remote version, so changes are synced between the two.

## Commit

A commit is similar to saving a file, with a bit more nuance. The commit (or revsion) is an individual change to a file. Every time a developer saves (or commits) with Git, it creates a unique ID that allows the developer to keep record of all changes made and by whom they were made. Even more helpful, each commit can contain a brief message describing the change made. Examples of commits include fixing a typo, updating a filename, or editing code. All commits are saved in the project's respository.

## Push

A push sends committed changes to a remote repository (often hosted on GitHub). After pushing, other collaboraters may access changes that a developer originally made locally.

## Pull

A pull happens when adding changes and merging them into the master branch. Pull requests are submitted by a user and then either accepted or rejected by the repository's collaborators. 

## Branch

A branch is a parallel version of a repository. In other words, it is contained within the repository, but does not affect the master branch. This allows a developer to work freely without disrupting the live version of the repository. Once the desired change are made, a branch can be merged back into the master branch, which publishes the changes.

## Merge

A merge takes the change from one branch and applies them into another. The changes can be from the same repository or from a fork. Merges can be done as a pull request or via the command line.

## Merge Conflict

Merge conflicts occur when branches are merged that have competing commits. In this case, Git asks the developer to decide which changes to incorporate into the final merge. Conflicts can occur, for example, when the changes are on different lines or in different files. All merge conflicts must be resolved before a pull request can be merged on GitHub.

## Fetch

To fetch means to get the latest changes from an online repository without merging them in. After fetching, a developer can compare these changes to the local branches.

## Remote

This is the version of something that is hosted on a server (most likely GitHub). In order for changes to be synced, it can be connected to local clones.

## References

https://help.github.com/en/articles/about-merge-conflicts#targetText=Merge%20conflicts%20happen%20when%20you,branches%20and%20merge%20them%20automatically.

https://help.github.com/en/articles/github-glossary#targetText=A%20commit%2C%20or%20%22revision%22,made%20when%20and%20by%20who.

https://www.atlassian.com/git/glossary/terminology


