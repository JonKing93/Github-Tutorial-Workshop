---
layout: lesson
title: Exercise 1
---

# Exercise 1: Create a new repository

In this exercise, we will create a new repository.

## A) Create a new repository

Open Github Desktop, select the "File" dropdown menu and choose the "New Repository" option.

<img src="..\assets\images\new.png" alt="Selecting a new repository from the file dropdown menu." style="max-width:374px;display:block">

After doing so, you will be presented with a window specifying options for creating the repository.

<img src="..\assets\images\new-options.png" alt="A window with options for creating a new repository." style="max-width:401px;display:block">

Let's walk through the different fields.

### Name

Here you should provide a name for your project. Use something memorable that would make sense to both you and any potential collaborators. Repository names can only use letters, numbers, hyphens, and underscores. Any other characters will be replaced with a hyphen.

### Description

A short 1-2 sentence description of the project that will be organized in this repository. This is an optional field, but it's a good idea to use it as this is the first step to documenting a project.

### Local Path

In order to track changes to a project, Github needs the contents of the project to be stored in a folder. This field specifies the location of that folder. You can either create a completely new folder (if building a project from scratch), or specify an existing folder on your computer that already contains a project.

For this workshop, go ahead and create a completely new folder so we can build a repository from scratch. Choose somewhere easy to access so you can return to this project throughout the workshop.

### Initialize with README

The next option is a checkbox indicating whether to initialize the project with a README file. A readme is a text document that can provide a summary or information about a project. Think of it as analogous to the abstract in a scientific paper. Creating a README is optional, but recommended and common practice with Github. For this workshop, go ahead and select the checkbox so that the repository includes a README.

### Gitignore

We'll come back to this later, but it's possible to specify certain files or types of files that Github should *not* track. For now, just leave this box alone.

### License

This box has options for automatically choosing a license for your project. A detailed discussion of licenses is beyond the scope of this workshop, but I'd encourage you to learn about them separately. For the most part, using no license retains the rights to a work with you. If you already know a license you'd like to use, go ahead and select it now. Otherwise, just leave this box as "None".

### Create

Once you've finished with the fields, you're ready to create a repository. Go ahead and click the "Create Repository" button.

## B) Explore the local repository

So you made a repository, nice! Go ahead and navigate to its folder on your computer (remember, this is wherever we set the local path). Inside you should see three items

1. A folder named ".git",
2. A file named .gitattributes
3. A file named README.md

It should look something like this:

<img src="..\assets\images\new-repo-contents.png" alt="The contents of the new repository." style="max-width:453px;display:block">

The ".git" folder and ".gitattributes" file include various settings and files required to make git and Github work properly. In general, you won't need to interact with them. The file "README.md" is the file created when we selected the README checkbox. The ".md" signifies a "markdown" file, which is a human-readable text file that also supports some formatting options (like italics, bold, and links). If you're curious, go ahead and open it in a text editor. You should see the repository name followed by its description.


<br>
# Exercise 1 Demo

My demo will be for a research project focused on finding the best recipe for salsa verde. I'm going to name the repository "salsa-demo" and use the description: "This is my project for finding the best recipe for salsa verde". I'm going to initialize it with a README, but no .gitignore or license.

<img src="..\assets\images\new-demo.png" alt="Creating a new repository for my demo project." style="max-width:404px;display:block">

Clicking the "Create Repository" button makes a new repository with the following structure.

INSERT FIGURE.

The contents of the README file are:

INSERT FIGURE.
