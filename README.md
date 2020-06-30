# Working Directory
- The working tree is a single checkout of one version of the project. 
These files are pulled out of the compressed database in the Git directory 
and placed on disk for you to use or modify.

# Staging Area
- The staging area is a file, generally contained in your Git directory, 
that stores information about what will go into your next commit. 
Its technical name in Git parlance is the “index”, 
but the phrase “staging area” works just as well.

# Git Repository
- The Git directory is where Git stores the metadata and object database for your project. 
This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

=============
GIT BRANCHES |
=============

# Git Branches

- Listing all branches
 
    * git branch
 
- Adding a Branch
    
    * git checkout -b (name of the new branch)

- Changing Branches
    * git checkout (name of the branch)

- Merging a Branch
    * git merge (name of the branch to merge)
    
- Removing a Branch
    * git branch -d (name of the branch to delete)
