# Working with Git

Git is mostly used to track code files, whether for a website, a mobile
app, a data analysis project, but not only. You could write a book and
track your files with Git. **This entire course was actually tracked
with Git while it was being created.**

Git is really useful to track any kind of text-based file. 
At its core, a “Git project” tracks files in a folder (if the folder contains folders, the files in these are tracked as well). 
A folder tracked by Git is called a “Git **Repository**”. 
So every time you decide to track a data science project with Git, it becomes a “Git Repository” (or “Git Repo” for short).

Few concepts that you need to know:

- A **Repository**: a folder that contains your project, and that is tracked with Git;
- A **Commit**: a commit is a snapshot of your work;
- A **Local repository**: the local version of the folder (i.e the folder on your computer that is tracked). A bit like the local version of a Dropbox folder;
- A **Remote repository**: the version on the internet (e.g. Github), that is connected to your local repository;
- To **push**: means to publish your local changes (your commit) to the remote repository;
- To **pull**: means to update the local repository, based on the changes tracked on the remote repository. You will typically do this to update your repository based on changes your collaborators made;
- To **clone**: to download a repository from Github to your local machine.

In the following illustration, you can see a simple workflow that you will try in the following unit and you will use to submit your first project. 
You will indeed first *create a repository* (repo) on Github, then *clone* it to your computer, make changes to it and take a snapshot of an important moment by creating a *commit*. 
You will then make your changes visible to us (or any collaborator) by *pushing* your commits to Github again.


<div data-type="Figure" data-permanent-id="c1_working_with_git_illustrations_016png" data-github-path="c1_working_with_git/illustrations_016.png" data-json="{"max_width": 800}"></div>
