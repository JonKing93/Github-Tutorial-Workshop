---
layout: lesson
title: Exercise 5
---

# Exercise 5: Gitignore

In this exercise, we will practice using a .gitignore to ignore files in the local repository. I'd encourage you to use files from a real project if you have any. Otherwise, you can download some dummy files to play with <a href="ignore.zip" download>here</a>.

## A) Test the ignored files

Move some files you'd like to ignore into the repository. Open up Github Desktop and you should see that the files will be added to the next commit. For example, I've added a two large data files to my project:

<img src="..\assets\images\repo-contents-ignore.PNG" alt="A file browser shows the addition of two data files: 1. salsa-database.mat, and 2. chile-data.nc." style="max-width:447px;display:block">

and can see them under the "Changes" tab in Github Desktop.

<img src="..\assets\images\ignore-1.png" alt="Github desktop lists the two new files under the changes tab." style="max-width:700px;display:block">

Note that Github Desktop cannot display the contents of these files because they are stored in a binary format. Again, Github is not designed to track changes to large files or data; it is primarily for plain text and code.

It's worth commenting that you could uncheck the files in Github Desktop to prevent them from being added to the next commit. For example, I could do:

<img src="..\assets\images\uncheck-ignore.png" alt="The check boxes beside salsa-database.mat and chile-data.nc in the Changes tab have been unchecked." style="max-width:700px;display:block">

to prevent the files from being added to the next commit. However, I would need to repeat this for every subsequent commit, which is not ideal. Instead, we'll use a .gitignore to always ignore the files. Before continuing, move the files back out of the repository.

## B) Create a .gitignore file

Create a new file named ".gitignore" in the root of your repository. For example

<img src="..\assets\images\new-ignore.png" alt="A file browser for the salsa repository now has a file named .gitignore." style="max-width:445px;display:block">

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

<img src="..\assets\images\repo-contents-ignore2.PNG" alt="A file browser for the salsa repository now has a file named .gitignore as well as the two data files." style="max-width:445px;display:block">

but the ignored files do not appear in Github Desktop

<img src="..\assets\images\ignored.png" alt="Github Desktop does not acknowledge the addition of the data files to the salsa repository." style="max-width:700px;display:block">

Alright, you should now have the tools to add all the file you need to your project's repository. Let's see how to use Github to track changes to those files and obtain a version history.

[Previous](05-gitignore)---[Next](exercise-6)
