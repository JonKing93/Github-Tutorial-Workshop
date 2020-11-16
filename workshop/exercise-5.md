---
layout: lesson
title: Exercise 5
---

# Exercise 5: Gitignore

In this exercise, we will practice using a .gitignore to ignore files in the local repository. If you like, you can download some example files to play around with <a href="..\demo-files\gitignore-demo-files.zip" download>here</a>.

## A) Test the ignored files

Move some files you'd like to ignore into the repository. Open up Github Desktop and you should see that the files will be added to the next commit. For example, I've added a two large data files to my project:

![A file browser shows the addition of two data files: 1. salsa-database.mat, and 2. chile-data.nc.](..\assets\images\E5\repo-contents-ignore.png)

and can see them under the "Changes" tab in Github Desktop.

![Github desktop lists the two new files under the changes tab.](..\assets\images\E5\ignore-1.png)

Note that Github Desktop cannot display the contents of these files because they are stored in a binary format. Again, Github is not designed to track changes to large files or data; it is primarily for plain text and code.

It's worth commenting that you could uncheck the files in Github Desktop to prevent them from being added to the next commit. For example, I could do:

![The check boxes beside salsa-database.mat and chile-data.nc in the Changes tab have been unchecked.](..\assets\images\E5\uncheck-ignore.png)

to prevent the files from being added to the next commit. However, I would need to repeat this for every subsequent commit, which is not ideal. Instead, we'll use a .gitignore to always ignore the files. Before continuing, move the files back out of the repository.

## B) Create a .gitignore file

Create a new file named ".gitignore" in the top level of your repository. For example

![A file browser for the salsa repository now has a file named .gitignore.](..\assets\images\E5\new-ignore.png)

## C) Write the .gitignore

Write the .gitignore so that it ignores the files. I'd recommend adding comments so you can use this .gitignore as a reference in the future. Here are the contents of the .gitignore for my salsa repository.

```
# Ignore the two database files
salsa-database.mat
chile-data.nc
```

## D) Commit the .gitignore

Use the commit box in the bottom left of Github desktop to commit the .gitignore file. Note that you must commit the file before Github will start ignoring files.

## E) Re-test the files

Move the files back in to the repository. Open Github Desktop. The files should no longer appear under the changes tab. For my salsa repository, I once again have:

![A file browser for the salsa repository now has a file named .gitignore as well as the two data files.](..\assets\images\E5\repo-contents-ignore2.png)

but the ignored files do not appear in Github Desktop

![Github Desktop does not acknowledge the addition of the data files to the salsa repository.](..\assets\images\E5\ignored.png)

Alright, you should now have the tools to add all the file you need to your project's repository. Let's see how to use Github to track changes to those files and obtain a version history.

[Previous](05-gitignore)---[Next](exercise-6)
