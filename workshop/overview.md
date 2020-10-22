---
layout: lesson
title: "Github: Overview"
---

# So, how does this all work?

Let's go over a quick overview of Github to illustrate some key concepts and vocabulary.

### Remote Repository

To begin: In order to use Github, the files for a project should be stored in a folder. This folder is known as a **repository** or **repo** for short. Ultimately, the repository will be backed up to the cloud on Github's servers; this cloud repository is known as the **remote repository**.

<img src="..\assets\images\remote.svg" alt="Remote repository located in the Github cloud." style="width:100%;display:block">

### Clone

To work on a project, you will need to download the repository to your computer. The repository on your computer is known as the **local repository**. The action of copying the remote repository to your computer is known as **cloning**.

<img src="..\assets\images\clone.svg" alt="Cloning the remote repository from the Github cloud to the local computer." style="width:100%;display:block">

### Commit

As you make changes to your project, you will want to periodically save it and document your work. When you do so, the current state of your project is saved and added to the project's version history. Each of these versions is known as a **commit**. Likewise the action of making these saves is also known as a **commit** or **committing**.

<img src="..\assets\images\commit.svg" alt="Committing a change to a file on the local computer." style="width:100%;display:block">

### Push

At this point, the commits are only stored on your local computer. So, after making a few commits, you will want to upload your changes back to the remote repository. This will ensure that your work is backed up and that the remote repository is up to date. The action of uploading your changes to the remote is known as a **push**.

<img src="..\assets\images\push.svg" alt="Pushing the new commit from the local computer to the Github cloud." style="width:100%;display:block">

### Additional Commits and Pushes

It's worth noting that you only need to clone the repository once. Once you have a local copy, git will track all changes you make. So you can make additional commits and push them ad infinitum.

<img src="..\assets\images\continue.svg" alt="Making additional commits and pushes." style="width:100%;display:block">

### Summary

Putting it all together:

<img src="..\assets\images\full-cycle.svg" alt="Essential steps of working with Github." style="width:100%;display:block">

<br>
# New Vocabulary

Locations
* **repository**: The folder where the files for a project are stored.
* **repo**: A repository.
* **remote**: A repository stored on the cloud.
* **local**: The repository stored on your computer.
* **commit**: A saved version of a repository.

Actions
* **clone**: Downloading a remote repository to your computer.
* **commit**: Saving a version of a project and documenting the changes.
* **push**: Uploading commits to the remote repository.

[Previous](git-vs-github)---[Next](new)
