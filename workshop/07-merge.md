---
layout: lesson
title: Branches
---

# Merging branches

As mentioned previously, you might branch your code so that you can maintain a working version while testing out new features that could break your code or analysis. However, once you finish developing the new features, you may want to consolidate the two branches.

INSERT FIGURE OF TWO BRANCHES READY TO COMBINE

This will ensure that your new features are incorporated into future analyses and will help keep your repository clean and easy to navigate. Combining two branches into one branch is known as **merging**.

INSERT FIGURE HIGHLIGHTING THE MERGE ZONE

# Merge conflicts

In many cases, merging is simple. As long as two branches do not alter the same lines of a file, the file can be merged seamlessly. For example, merging these two ingredients lists can be done automatically because they alter different lines of the file.

<div style="display:flex;flex-flow:row wrap;justify-content:space-between;">
<pre class="highlight" style="width:45%;">
<code>Contents 1</code>
</pre>
<pre class="highlight" style="width:45%;">
<code>Contents 2</code>
</pre>
</div>
```
Contents 3
With a new line
And another
```

FILE CONTENTS EXAMPLE SIDE BY SIDE THEN MERGED

However, attempting to merge two branches that alter the same part of a file will result in an error known as a **merge conflict**. For example, the following example would cause a merge conflict because both branches edit the ??? line.

FILE CONTENTS SIDE BY SIDE

To resolve a merge conflict, choose a desired version of the line and copy it into the other branch.

# New Vocabulary

* **merge**: Combining two branches
* **merge conflict**: An error that occurs when trying to merge branches that have different versions of the same line.


In the next exercise, we will practice merging branches and resolving a merge conflict.

[Previous](exercise-8)---[next](exercise-9)
