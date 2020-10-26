---
layout: lesson
title: Exercise 5
---

# Exercise 5: Gitignore

In this exercise, we will practice using a .gitignore to ignore files in the local repository. I'd encourage you to use files from a real project if you have any. Otherwise, you can download some dummy files to play with <a href="ignore.zip" download>here</a>.

## A) Test the ignored files

Move some files you'd like to ignore into the repository. Open up Github Desktop and you should see that the files will be added to the next commit. For example

INSERT FIGURE

Note that you could uncheck the files to prevent them from being added to the next commit. For example, I could do

INSERT FIGURE

to prevent the files from being added to the next commit. However, I would need to repeat this for every subsequent commit, which is not ideal. Instead, we'll use a .gitignore. Before continuing, move the files back out of the repository.

## B) Create a .gitignore file

Create a new file named ".gitignore" in the root of your repository. For example

INSERT FIGURE

## C) Write the .gitignore

Write the .gitignore so that it ignores the files. I'd recommend adding comments so you can use this .gitignore as a reference in the future. Here are the contents of the .gitignore for my salsa repository.

INSERT CONTENTS

## D) Commit the .gitignore

Use the commit box in the bottom left of Github desktop to commit the .gitignore file. Note that you must commit the file before Github will start ignoring files.

## E) Re-test the files

Move the files back in to the repository. Open Github Desktop. The files should no longer appear under the changes tab. For my salsa repository, I now have:

INSERT FIGURE

but the ignored files do not appear

INSERT FIGURE


Alright, you should now have the tools to add all the file you need to your project's repository. Let's see how to use Github to track changes to those files and obtain a version history.

[Previous](05-gitignore)---[Next](exercise-6)
