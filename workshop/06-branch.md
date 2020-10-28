---
layout: lesson
title: Branches
---

# Branches

So far, all of our version histories have been sequential. Each commit follows the next in an ordered line. For example:

INSERT FIGURE

However, sometimes it can be useful to manage different versions of code simultaneously. For example, you may have a script that performs some sort of scientific analysis, but want to use different parameters or settings for different ongoing analyses. Alternatively, you may want to have a version where you can test out new features while maintaining a version you know already works. In this case, our version history might look something like this:

INSERT FIGURE

In git parlance, these concurrent versions are known as **branches**. Branches are derived from some common point in a version history, but each branch will have a unique history after the split point. For example,

INSERT FIGURES SHOWING HISTORY FOR DIFFERENT BRANCHES

You can then switch between different branches and add new commits as your needs dictate.

# New Vocabulary

* **branches**: Concurrent versions of a repository.


In the next exercise, we will see how to create and commit to different branches.

[Previous](exercise-7)---[Next](exercise-8)
