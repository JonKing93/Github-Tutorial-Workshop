---
layout: lesson
title: Github fundamentals
---

# So, how does this all work?

Let's go over a quick overview of Github to illustrate some key concepts and vocabulary.

### Remote Repository

To begin: In order to use Github, the files for a project should be stored in a folder. This folder is known as a **repository** or **repo** for short. Ultimately, the repository will be backed up to the cloud on Github's servers; this cloud repository is known as the **remote repository**.

![An icon of a folder with some files. The folder is in the Github cloud and is labeled 'Remote'.](..\assets\images\03\remote.svg)

### Clone

To work on a project, you will need to download the repository to your computer. The repository on your computer is known as the **local repository**. The action of copying the remote repository to your computer is known as **cloning**.

![An arrow points from the remote to a second folder with files on the user's local computer. The arrow is labeld 'clone'. The folder on the local computer is labeled 'local'.](..\assets\images\03\clone.svg).

### Commit

As you make changes to your project, you will want to periodically save and document your work. When you do so, the current state of your project is saved and added to the project's version history. Each of these versions is known as a **commit**. Likewise the action of making these saves is also known as a **commit** or **committing**.

![An arrow advances the local files to an edited state. The arrow is labeled 'commit'.](..\assets\images\03\commit.svg)

### Push

At this point, the commits are only stored on your local computer. So, after making a few commits, you will want to upload your changes back to the remote repository. This will ensure that your work is backed up and that the remote repository is up to date. The action of uploading your changes to the remote is known as a **push**.

![An arrow points from the edited file to a copy on the Github cloud. The arrow is labeled 'push'.](..\assets\images\03\push.svg)

### Additional Commits and Pushes

It's worth noting that you only need to clone the repository once. Once you have a local copy, git will track all changes you make, so you can continue make additional commits and pushes quickly and efficiently.

![Additional arrows advance the files through more edits. These are labeled 'commit'. Other arrows upload the edited files to the cloud. These are labeled 'push'.](..\assets\images\03\continue.svg)

### Summary

Putting it all together:

![The cycle of working with Github. Download (clone) a remote repository. Commit edits to the repository. Upload (push) those edits to the cloud.](..\assets\images\03\full-cycle.svg)

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

(Note: There is a glossary of all the terms introduced in the workshop under the "Concepts" tab.)

[Previous](02-git-vs-github)---[Next](04-publish)
