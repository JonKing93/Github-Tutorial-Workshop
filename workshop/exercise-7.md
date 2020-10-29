---
layout: lesson
title: Exercise 7
---

# Exercise 7: Revert Bad Commits

Sometimes, you might commit changes that break your code or analysis. Fortunately, the version history makes it easy to undo such changes.

## A) Make a bad commit

Edit a file in a way that messes up your project and commit it. For example, here I've accidentally modified the ingredients list to use 3 gallons of salt.

<img src="..\assets\images\bad-commit.png" alt="The changes tab shows that the ingredient list has been altered to use 3 gallons of salt." style="max-width:700px;display:block">

## B) Revert the commit

Open Github Desktop and open the "History" tab. Right click the bad commit and select the "Revert this commit" option. For example, here is how I would revert the bad commit in the salsa repository.

<img src="..\assets\images\revert.png" alt="In the history tab, the bad commit is selected. A dropdown menu includes the option to revert the commit." style="max-width:700px;display:block">

This will add a new commit to the version history that undoes the changes made in the bad commit. For example, my version history now looks like:

<img src="..\assets\images\reverted.png" alt="In the history tab, the bad commit is reverted. The right side indicates that the ingredients list has changed back to its original state." style="max-width:700px;display:block">

Note that you are not limited to reverting the most recent commit. You can revert ***any*** commit in your version history.

## C) Download the code from an old commit

In some situations, it can be useful to download the entire repository from some point in its version history. To do this, go online to the remote repository and navigate to the version history via the "Commits" button in top right of the code panel. On the right side of each commit is a button with two angle brackets. For example:

<img src="..\assets\images\brackets.png" alt="In the version history for the remote repository, the angle bracket button on the right side of each commit is highlighted." style="max-width:700px;display:block">

Clicking on this button will take you to the repository at that point in the version history (the point immediately after the commit was made). For example, if I click on the angle brackets for the "Increased boiling time" commit:

<img src="..\assets\images\brackets2.png" alt="In the version history for the remote repository, the angle bracket button for the boiling time commit is highlighted." style="max-width:700px;display:block">

then I will be taken to the point in the version history immediately after editing those files.

<img src="..\assets\images\browse.png" alt="The files at the point of the old commit are displayed in the remote repository's code window." style="max-width:700px;display:block">

Use the green "Code" button in the upper right to download the old version of the code or open it in Github Desktop.

<img src="..\assets\images\download.png" alt="The green code button has a red arrow pointing to it. From the button, a dropdown menu includes the option to download the code." style="max-width:700px;display:block">


So far, our version history has always proceeded in a sequential manner. A new commit always follows the old commits in a line. However, it can also be useful to work with multiple versions your code simultaneously. In the next sections, we will see how to use branches to do so.

[Previous](exercise-6)---[Next](06-branch)
