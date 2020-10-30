---
layout: lesson
title: Branches
---

# Merging branches

As mentioned previously, you might branch your code so that you can maintain a working version while testing out new features that could break your code or analysis. However, once you finish developing the new features, you may ready to consolidate the two branches.

![The main branch has a second branch for developing a new feature. The second branch has reached a commit labeled 'Finished new feature'.](..\assets\images\07\pre-merge.svg)

This will ensure that your new features are incorporated into future analyses and will help keep your repository clean and easy to navigate. Combining two branches into one branch is known as **merging**.

![A line now joins the last commit of the new feature branch to the main branch. A commit at the end of this line is labeled 'Merge new feature'.](..\assets\images\07\merge.svg)

Note that when you perform a merge, the history of both branches are also combined.

![The commits on the new feature branch have been added to the main branch after merging.](..\assets\images\07\merge-history.svg)

# Automatic Merges

In many cases, merging is simple. As long as two branches do not alter the same lines of a file, the file can be merged seamlessly. For example, say this is the ingredients list at a branch point:
```
8 Tomatillos, peeled and washed
2 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt
```

Then, the following two ingredients lists:

<div style="display:flex;flex-flow:row wrap;justify-content:space-between;">

<pre class="highlight" style="width:45%;">
<code>8 Tomatillos, peeled and washed
3 Jalapenos, seeds and stems removed
1/4 white onion
3 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt</code>
</pre>

<pre class="highlight" style="width:45%;">
<code>8 Tomatillos, peeled washed and cut in half
2 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt</code>
</pre>

</div>

can be merged automatically because they alter different lines of the file. The left file changes the amount of jalapenos and garlic, while the right file alters the preparation instructions for the tomatillos. The file merged file would be:
```
8 Tomatillos, peeled washed and cut in half
3 Jalapenos, seeds and stems removed
1/4 white onion
3 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt
```


# Merge conflicts

However, sometimes files cannot be merged automatically. This occurs when two branches alter the same lines of a file. The git tools don't know which version of the line to use and cannot proceed; this situation is known as a **merge conflict**. For example, if the following file is the ingredient list at the branch point:

```
8 Tomatillos, peeled and washed
2 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt
```

Then the following two files:

<div style="display:flex;flex-flow:row wrap;justify-content:space-between;">

<pre class="highlight" style="width:45%;">
<code>8 Tomatillos, peeled and washed
3 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt</code>
</pre>

<pre class="highlight" style="width:45%;">
<code>8 Tomatillos, peeled and washed
4 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt</code>
</pre>

</div>
would cause a merge conflict because they both edit the jalapenos line.

To resolve a merge conflict, choose a desired version of the line and copy it into the other branch.

# New Vocabulary

* **merge**: Combining two branches
* **merge conflict**: An error that occurs when trying to merge branches that have different versions of the same line.


In the next exercise, we will practice merging branches and resolving a merge conflict.

[Previous](exercise-8)---[next](exercise-9)
