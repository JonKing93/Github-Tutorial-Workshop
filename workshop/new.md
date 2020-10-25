---
layout: lesson
title: Create a Repository
---

# Create a new repository

Before we can clone a repository and start making commits, we will need to create a new repository and publish it on the Github cloud. To do so: open Github Desktop, select the "File" dropdown menu, and choose the "New Repository" option.

<img src="..\assets\images\new.png" alt="Selecting a new repository from the file dropdown menu." style="max-width:374px;display:block">

After doing this, you will being presented with a window specifying options for creating the repository.

<img src="..\assets\images\new-options.png" alt="Selecting a new repository from the file dropdown menu." style="max-width:401px;display:block">

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

Once you've finished with the fields, you're ready to create a repository. Nice! Go ahead and click the "Create Repository" button.

<br>
# Demo

In my demo, I'm going to create a repository for a research project focused on finding the best recipe for salsa verde. I'm going to name the repository "salsa-demo", and the description: "This is my project for finding the best recipe for salsa verde". I'm going to initialize it with a README, but no .gitignore or license.

<img src="..\assets\images\new-demo.png" alt="Creating a new repository for my demo project." style="max-width:404px;display:block">


[Previous](overview)---[Next](publish)
