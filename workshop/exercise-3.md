---
layout: lesson
title: Exercise 3
---

# Exercise 3: Commit new files to the repository

Now that we've created and published the repository, we're going to start adding the files for our project.

## A) Add a file to the local repository

Move a project file into the local repository on your computer. This can be almost anything, but a code file is a good place to start.

**Important**: Github is designed to manage code, not large databases. Trying to commit files larger than 100MB will cause errors, so stick with something small.

I'm going to add a file named "ingredients.txt" to my demo repository.

<img src="..\assets\images\repo-contents-2.PNG" alt="A file browser for the salsa repository now includes a file named 'ingredients.txt'." style="max-width:450px;display:block">

This is the ingredients list for my salsa recipe. The contents of ingredients.txt are:

```
8 Tomatillos
2 Jalapenos, seeds and stems removed
1/4 white onion
2 garlic cloves, peeled
1 bunch fresh cilantro, roughly chopped
1/2 t salt
```

## B) Examine the new file

Open up Github Desktop. On the left side, under the "Changes" tab, you should see the name of the new file. The file name should be followed by a green plus, indicating that this is a new addition to the repository. On the right side, you can see the contents of the new file. For example, I have:

<img src="..\assets\images\add-file.png" alt="Github desktop shows the name of the new 'ingredients.txt' file on the left side, and the contents of the file on the right side." style="max-width:450px;display:block">

## C) Commit the new file

We're going to commit this file so that it's added to the repository. This way, Github will be able to track any future changes we make. At the bottom left of Github desktop, you should see the commit interface.

<img src="..\assets\images\commit.png" alt="A snapshot of Github Desktop with an arrow point to the commit interface in the bottom left." style="max-width:700px;display:block">

Zooming in, you can see that the commit interface consists of three pieces:
<img src="..\assets\images\commit-box.png" alt="A zoomed view of the Github Desktop commit interface with three fields." style="max-width:241px;display:block">

### Commit message
The top field in the interface is the commit message. This is required for every commit and lets you record the changes you've made to the project.

### Commit description
The middle of the interface is a field that lets you provide a more detailed description of the commit. This is optional but lets you provide more details about changes. You can also acknowledge collaborators for the commit using the button in the bottom left.

### Commit button
Once you finish the commit message (and optionally the description), click the button to make the commit.

Go ahead and fill out the commit message and click the button to make the commit. For example, I used:

<img src="..\assets\images\demo-add.png" alt="A zoomed view of the Github Desktop commit interface the commit message filled out. The message indicates that an ingredient list was added to the demo." style="max-width:242px;display:block">

Congratulations, you just made your first commit!

[Previous](exercise-2)---[Next]
