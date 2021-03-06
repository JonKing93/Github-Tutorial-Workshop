---
layout: lesson
title: Exercise 4
---

# Exercise 4: Push the new file

Now that you've added a file to the project, you'll want to push it to the remote repository. This way, the file is backed up and accessible to collaborators.

## A) Examine the remote repository

Navigate back to the remote repository. You'll see that the new file does not appear in its contents. For example, my salsa repository does not contain the ingredients list:

![The contents of the remote repository does not contain 'ingredients.txt'.](..\assets\images\E4\repo-code.png)

This is because we have not yet uploaded our commit by pushing it to the cloud.

## B) Push the commit

Open Github Desktop. The top right tab should now say "Push origin" and display the number of commits waiting to be pushed. Click this tab to push your commits

![The top right tab in Github Desktop says 'Push Origin'. An arrow points at the tab.](..\assets\images\E4\push.png)

## C) Re-examine the remote repository

Head back to the remote repository. It should now include the newly added file. (Note that you may need to refresh the browser page first). For example, my salsa repository now has:

![The remote repository now includes the file 'ingredients.txt'.](..\assets\images\E4\repo-contents-3.png)

## D) Practice practice practice

Add some more project files to your repository. These could include markdown, code, figures, etc. so long as the file size is under 100MB. Commit and push the new files. Note that you can add multiple files with a single commit. For example, here I am adding several files to the salsa repository:

![Github Desktop shows the addition of three files: 1. ingredients.txt, 2. research-notes.txt, and 3. salsa_verde.m.](..\assets\images\E4\add-file3.png)

Looking at the left side, you can see the salsa repository now includes plain-text instructions, Matlab code implementing the salsa verde, as well as some research notes.

At this point, you should have a repository built up with a number of files pertaining to your project. Soon we will see how to use Github to track changes to these files and obtain a version history. However, it's worth noting that there are some files that you may not want Github to track. In the next section, we will see how to use a gitignore to keep unwanted files out of a repository.

[Previous](exercise-3)---[Next](05-gitignore)
