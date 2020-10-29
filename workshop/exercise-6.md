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

<img src="..\assets\images\track.png" alt="Github Desktop displays the 'ingredients.txt' file under the changes tab. The right side shows the contents of the file, along with red and green backgrounds that indicate the edits made." style="max-width:700px;display:block">

You can use the red and green backgrounds to see how I changed the file.

## C) Practice committing edits

Commit your edited file and make at least two more commits. For example, I'm going to increase the boiling time to 10 minutes and update my research notes. Note that you can change multiple files with a single commit. For example, here I changed both the instructions and code files.

<img src="..\assets\images\track2.png" alt="Github Desktop shows that the recipe instructions and code file have changed. The changes to the instructions are shown on the right side." style="max-width:700px;display:block">

Note that you can examine the changes to different files by selecting them in the "Changes" tab. For example, if I wanted to see the changes to salsa_verde.m, I would do:

<img src="..\assets\images\track3.png" alt="Github Desktop shows that the recipe instructions and code file have changed. A red arrow labeled 'select a file' points to the code file. The changes to the code are shown on the right." style="max-width:700px;display:block">

## D) Examine the version history

By making these commits, you've saved multiple versions of your work. Click on the "History" tab to see the version history for your project.

<img src="..\assets\images\history-tab.png" alt="A red arrow points to the history tab in the upper left of Github Desktop." style="max-width:700px;display:block">

On the left hand side, you should see a list of all the commits you've made to the project. When you click on one of these commits, the middle of the screen will display the files changed in that commit, and the right side will show the changes to the selected file. For example, here is the version history for the commit where I added the ingredients list.

<img src="..\assets\images\history1.png" alt="Github Desktop shows the version history of commits on the left side. The commit that increased boiling time is selected, and the file changes for that commit are displayed on the right side." style="max-width:700px;display:block">

## E) Version history via the remote repository

If you have not pushed your commits, go ahead and do so now. Head online to the remote repository and check out the code panel. Note that the text to the right of each file is the commit message for the most recent commit that altered the file.

<img src="..\assets\images\remote-history.png" alt="The code window of the remote repository displays the most recent commit message to the right of each file." style="max-width:700px;display:block">

In the upper right corner is a "Commits" button. Click on it.

<img src="..\assets\images\history-button.png" alt="A red arrow points to the 'Commits' button in the upper right of the remote repository's code window." style="max-width:700px;display:block">

This will also take you to the version history for the repository. For example, I have:

<img src="..\assets\images\remote-history2.png" alt="A version history for the salsa repository is displayed online." style="max-width:700px;display:block">

for the salsa demo. Clicking on any of these commits will allow you to browse the changes made to the relevant files.


A version history can be valuable for documenting progress and changes to a research project. However, it can also be useful for removing unwanted changes or updates that break your code. In the next exercise, we will see how to use the version history to revert bad commits.

[Previous](exercise-5)---[Next](exercise-7)
