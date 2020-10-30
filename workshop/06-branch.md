---
layout: lesson
title: Branches
---

# Branches

So far, all of our version histories have been sequential. Each commit follows the next in an ordered line. For example:

![A single black line extends across the frame. Several points are marked; each point is a commit.](..\assets\images\06\linear-commits.svg)

However, sometimes it can be useful to manage different versions of code simultaneously. For example, you may have a script that performs some sort of scientific analysis, but want to use different parameters or settings for different ongoing analyses. Alternatively, you may want to have a version where you can test out new features while maintaining a version you know already works. In this case, our version history might look something like this:

![After the second commit, the line branches into three lines. The middle line is still black and has a commit labeled 'Set parameters'. The top line is blue and has a commit labeled 'Set different parameters'. The bottom line is red and has two commits. The first is labeled 'Start new feature' and the second is labeled 'Debugging'.](..\assets\images\06\branch.svg)

In git parlance, these concurrent versions are known as **branches**. Branches are derived from some common point in a version history, but each branch will have a unique history after the split point. For example, this is the version history for the default branch:

![The history includes the first two commits and the 'Set parameters' commit.](..\assets\images\06\branch-history-1.svg)

whereas this is the version history for the branch implementing a new feature:

![The history includes the first two commits, the 'Start new feature' commit, and the 'Debugging' commit.](..\assets\images\06\branch-history-2.svg)


You can then switch between different branches and add new commits as your needs dictate.

# New Vocabulary

* **branches**: Concurrent versions of a repository.


In the next exercise, we will see how to create and commit to different branches.

[Previous](exercise-7)---[Next](exercise-8)
