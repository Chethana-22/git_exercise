## Hello, world!

To run `feature-3`, execute `python3 three.py`
To run `feature-4`, execute `python3 four.py`
To run `feature-5`, execute `python3 five.py`
To run `feature-6`, execute `python3 six.py`




# Git Commonly Used Commands 

### What is **Git** ?

+ Manage projects with *Repositories*
* Clone a project to work on a local copy
- Control and track changes with Staging and Committing
+ Branch and Merge to allow for work on different parts and versions of a project
* Pull the latest version of the project to a local copy
- Push local updates to the main project

### What is **GitHub** ?

- Git is not the same as GitHub.
+ GitHub makes tools that use Git.
* GitHub is the largest host of source code in the world, and has been owned by ***Microsoft since 2018***.
- In this tutorial, we will focus on using Git with GitHub.

> Here's how to create a pull request

#### 1. Clone the repository
 Use `git clone` command to clone the repository of the project you intent to contribute and change the directory. *git clone* command creates a local copy of the repository, including all its history and branches

 ```
 git clone <repo link>
 cd repo_name

 ```

#### 2. Create a new branch
 Use `git branch` command to create a new branch. *git branch* command can be used to list all the existing branches and also create or delete a branch and also switches to the created new branch.

 ```
 git checkout -b branch branch_name 

 ```

#### 3. Make your changes
 Make the necessary code details either add, delete or edit the code base

#### 4. Stage your changes
 Use `git add ` command to stage your code changes. *git add* command adds the changes to the staging area, where they will be included in the next commit.

 ```
 git add .

 ``` 

#### 5. Commit the changes
 Use `git commit` command to commit the changes to the branch. *git commit* command records the staged changes and additional changes made since the last commit, along with the commit messages.

 ```
 git commit -m "commit message"

 ```

#### 6. Push your branch
 Use `git push` command to push all the committed changes. *git push* command sends the local commit to the specified remote repository, updating the branch on remote with the new commits

 ```
 git push origin main

 ``` 

#### 7. YAY! :ghost: Congratulations 
 Now the remote repository owner will review your code changes and discuss with you if any changes required and merge your changes to the main branch. You have contributed to a large code base :boom:


## HERE ARE SOME RESOURCES TO LEARN MORE ABOUT GIT

[^1]: [W3 Schools](https://www.w3schools.com/git/git_intro.asp?remote=github)
[^2]: [Git Documentation](https://git-scm.com/doc)
[^3]: [FreeCodeCamp](https://www.youtube.com/watch?v=RGOj5yH7evk)