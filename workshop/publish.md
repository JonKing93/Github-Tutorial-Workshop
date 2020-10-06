---
layout: lesson
title: Publish
---

# The new repository

So you made a repository, nice! Go ahead and navigate to its folder on your computer (remember, this is wherever we set the local path). Inside you should see three items

1. A folder named ".git",
2. A file named .gitattributes
3. A file named README.md

The first two include various settings and files required to make git and Github work properly. In general, you won't need to interact with them. The file "README.md" is the file created when we selected the README checkbox. The ".md" signifies a "markdown" file, which is a human-readable text file that also supports some formatting options. Go ahead and open it in a text editor if you're curious. You should see the repository name followed by its description. For example, the README for my salsa demo looks like:

<img src="..\assets\images\salsa-readme.png" alt="Creating a new repository for my demo project." style="max-width:646px;display:block">

# Publish the new repository to the cloud

Now that we've created the repository, we'll want to **publish** it. Publishing creates the remote repository on the cloud that you can use to back up and share your code. In Github Desktop, you should see three tabs near the top of the screen. The left tab lists the current repository. When you created the new repository, Github Desktop should have automatically set it as the current repository. For example, after creating the "salsa-demo" repository, I have:

<img src="..\assets\images\left-tab.png" alt="The new repository as the current repository." style="max-width:737px;display:block">

If your current repository is something other than the new repository, click on the left tab and select the new repository from the dropdown menu.

Now look at the right tab. It should be marked with the option "Publish Repository". Click on the tab

<img src="..\assets\images\right-tab.png" alt="Publishing a new repository for my demo project." style="max-width:724px;display:block">

This will open a box showing the name and description of the repository. There is also an option to make the repository public or private. (There is also an option to publish to a Github Enterprise server instead of Github.com, but we will not be using this for the workshop.)

<img src="..\assets\images\publish.png" alt="The box with options for publishing." style="max-width:448px;display:block">

# Public vs. Private

When you publish a repository as a public repository, it can be viewed by anyone on Github. By contrast, a private repository is only visible to you and invited collaborators. If your project contains sensitive information, you'll probably want to use a private repository. Otherwise, I encourage you to make your repositories public for several reasons:

#### 1. Ease of access
Quite simply, public repositories make it easier for collaborators to find and access your work.

#### 2. Scientific transparency
Public repositories support transparency and reproducibility, key tenets of scientific research. By making your code public, you ensure it is available for other researchers trying to reproduce or build on your work.

#### 3. Supports better coding
It can be intimidating to think of other people being able to see your code. This might just be me, but I find that this actually improves my code. When I think other people might want to see/use my code, I spend more time commenting and documenting the various features. I also tend to avoid shortcuts that might break the code further down the road. In the long run, this makes my code better and saves a significant amount of time.

#### 4. Greater control over a project
When your code is in a public repository, collaborators can suggest modifications, but these changes will require your approval before they can go into affect. Curiously, changes to a private repository do not require your approval. So a collaborator could alter (or break!) your code. So a public repository can be preferable if you want to retain control over your version of the code.

Once you select a setting for your project, go ahead and click the "Publish Repository" button.

# Demo

For the demo repository, I am choosing to use a public repository.

<img src="..\assets\images\demo-publish.png" alt="Publishing a new repository for my demo project." style="max-width:448px;display:block">


[Previous](new)---[Next](remote)
