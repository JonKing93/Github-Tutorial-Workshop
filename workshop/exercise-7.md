---
layout: lesson
title: Exercise 6
---

# Exercise 7: Revert Bad Commits

Sometimes, you might commit changes that break your code or analysis. Fortunately, the version history makes it easy to undo such changes.

## A) Make a bad commit

Edit a file in a way that messes up your project and commit it. For example, here I've accidentally modified the recipe to use 3 gallons of salt.

INSERT FIGURE

## B) Revert the commit

Open Github Desktop and open the "History" tab. Right click the bad commit and select the "Revert this commit" option. For example, here is how I would revert the bad commit in the salsa repository.

INSERT FIGURE

This will add a new commit to the version history that undoes the changes made in the bad commit. For example, my version history now looks like:

INSERT FIGURE

Note that you are not limited to reverting the most recent commit. You can revert ***any*** commit in your version history.

## C) Download the code from an old commit

In some situations, it can be useful to download the entire repository from some point in its version history. To do this, go online to the remote repository and navigate to the version history via the "Commits" button in top right of the code panel. On the right side of each commit is a button with two angle brackets. For example:

INSERT FIGURE

Clicking on this button will take you to the repository at that point in the version history (the point immediately after the commit was made). For example, if I click on the angle brackets for the ??? commit:

INSERT FIGURE

then I will be taken to the point in the version history before I made any changes to the instructions and ingredients list.

INSERT FIGURE

Use the green "Code" button in the upper right to download the old version of the code or open it in Github Desktop.

INSERT FIGURE


So far, our version history has always proceeded in a sequential manner. A new commit always follows the old commits in a line. However, it can also be useful to work with multiple versions your code simultaneously. In the next sections, we will see how to use branches to do so.

[Previous](exercise-6)---[Next](06-branch)
