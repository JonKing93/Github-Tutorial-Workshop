---
layout: lesson
title: gitignore
---

# Ignoring files in a repository

Sometimes, there may be files in your local repository that you do not want to commit to the project. There are several common reasons for this.

### 1. Large data files

As mentioned in exercise 3, Github is designed to track code and small text files rather than large databases. Consequently, trying to commit and push a file larger than 100MB will result in errors. However, large data files are common and often necessary in scientific research projects, so it can be useful to have them in the local repository without committing them.

Some common file extensions for data files include:
* .dat,
* .csv,
* .xlsx,
* .nc,
* .mat, and
* .hdf,
but there are many more.

### 2. Automatically generated files

Depending on your computer and the programs you use, various files can be automatically created in your local repository. Some examples include:
* Macs: .DS_Store (contains information for file browsing)
* Matlab: .asv (an autosave file)
* R: Could use some input here...
* Python: Could use some input here...

<br>
# Gitignore

You can use a .gitignore file to ensure that certain files / types of files are ignored in your repository. This is a **plain text file named ".gitignore"** stored at the root of your repository (in the same folder as the .gitattributes file and .git folder). I will focus on a few basic scenarios, but there are many complex options for using .gitignore files beyond the scope of this workshop. For those interested, the complete documentation for .gitignore can be found [here](https://git-scm.com/docs/gitignore) and a nice summary for the syntax can be found [here](https://www.atlassian.com/git/tutorials/saving-changes/gitignore).

### Comments

You can make any line in a .gitignore file a comment by starting it with a hashtag character (#). For example:
```
# This line is a comment.
```

### Ignore a specific file
You can use a line of a .gitignore to ignore a specific file by providing the file name. For example:
```
my-database-file.nc
```
would cause the repository to ignore the file "my-database-file.nc".

### Ignore all files with a particular extension
You can use a line of a .gitignore to ignore files with a particular extension by using two asterisks followed by the file extension. For example
```
**.dat
**.DS_Store
**.nc
```
would ignore all files ending in ".dat", ".DS_Store", or ".nc".

### Ignore files in a particular folder
You can use a line of a .gitignore to ignore files in a particular folder by specifying the name of the folder followed by a slash. For example
```
My-Data-Folder/
```
would ignore all files stored in "My-Data-Folder".

### Summary

Putting it all together, a real .gitignore might look something like this:
```
# Ignore large files
**.dat
**.nc

# Ignore auto-generated files
**.DS_Store
**.asv

# Ignore specific files
todo-list.txt
this-crummy-file.txt

# Ignore anything in my database folder
My-Data-Folder/
```

<br>
# New Vocabulary
* **gitignore**: A plain text file named '.gitignore' located at the repository root. The gitignore specifies files that should be ignored in the repository.

Alright, let's try it out!

[Previous](exercise-4)---[Next](exercise-5)
