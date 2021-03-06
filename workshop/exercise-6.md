---
layout: lesson
title: Exercise 6
---

# Exercise 6: Track Changes and Version History

Now that you've added files to your repository, you can use Github to record all your edits. In this exercise, you will use Github to track changes to your files and obtain a version history.

## A) Edit a file

Make some edits to a file in your repository. For example, I am adding a bit more information to the ingredients list. The updated "ingredients.txt" file now looks like:

```
8 Tomatillos, peeled and washed
2 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt
```

## B) Examine the changes

Open up Github Desktop and look at the left hand side. Under the Changes tab, you should see the name of the edited file followed by a yellow dot (which indicates the file has been edited). On the right hand side, you can see the contents of the edited file. Git tracks changes to each line of a file, and you can see those changes here. A green background indicates a line has been added to a file, while a red background indicates that a line has been deleted. Lines with a white background have not been altered. For the salsa repository, I have:

![Github Desktop displays the 'ingredients.txt' file under the changes tab. The right side shows the contents of the file, along with red and green backgrounds that indicate the edits made.](..\assets\images\E6\track.png)

You can use the red and green backgrounds to see how I changed the file.

## C) Practice committing edits

Commit your edited file and make at least two more commits. For example, I'm going to increase the boiling time to 10 minutes and update my research notes. Note that you can change multiple files with a single commit. For example, here I changed both the instructions and code files.

![Github Desktop shows that the recipe instructions and code file have changed. The changes to the instructions are shown on the right side.](..\assets\images\E6\track2.png)

Note that you can examine the changes to different files by selecting them in the "Changes" tab. For example, if I wanted to see the changes to salsa_verde.m, I would do:

![Github Desktop shows that the recipe instructions and code file have changed. A red arrow labeled 'select a file' points to the code file. The changes to the code are shown on the right.](..\assets\images\E6\track3.png)

## D) Examine the version history

By making these commits, you've saved multiple versions of your work. Click on the "History" tab to see the version history for your project.

![A red arrow points to the history tab in the upper left of Github Desktop.](..\assets\images\E6\history-tab.png)

On the left hand side, you should see a list of all the commits you've made to the project. When you click on one of these commits, the middle of the screen will display the files changed in that commit, and the right side will show the changes to the selected file. For example, here is the version history for the commit where I added the ingredients list.

![Github Desktop shows the version history of commits on the left side. The commit that increased boiling time is selected, and the file changes for that commit are displayed on the right side.](..\assets\images\E6\history1.png)

## E) Version history via the remote repository

If you have not pushed your commits, go ahead and do so now. Head online to the remote repository and check out the code panel. Note that the text to the right of each file is the commit message for the most recent commit that altered the file.

![The code window of the remote repository displays the most recent commit message to the right of each file.](..\assets\images\E6\remote-history.png)

In the upper right corner is a "Commits" button. Click on it.

![A red arrow points to the 'Commits' button in the upper right of the remote repository's code window.](..\assets\images\E6\history-button.png)

This will also take you to the version history for the repository. For example, I have:

![A version history for the salsa repository is displayed online.](..\assets\images\E6\remote-history2.png)

for the salsa demo. Clicking on any of these commits will allow you to browse the changes made to the relevant files.


A version history can be valuable for documenting progress and changes to a research project. However, it can also be useful for removing unwanted changes or updates that break your code. In the next exercise, we will see how to use the version history to revert bad commits.

[Previous](exercise-5)---[Next](exercise-7)
