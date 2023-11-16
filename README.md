# How to create a file using terminal and connecting it to a terminal 
## git-init-sample


### Create a directory for your project:

<p>mkdir git-init-file</p>
<p>cd git-init-file</p>

<p>mkdir: This command creates a new directory (folder) named "git-init-file."</p>
<p>cd: This command changes your current working directory to the newly created "git-init-file."</p>

### Initialize Git in the directory:

<p>git config --global init.defaultBranch main</p>

git config --global init.defaultBranch main: This sets the default branch name to "main" when initializing a new Git repository.

### Create an HTML file:
touch index.html

touch: This command creates a new empty file named "index.html."

### Check the status and initialize the Git repository:
git status
git init

git status: This command shows the status of your Git repository, indicating any untracked or modified files.
git init: This initializes a new Git repository in the current directory.

### Add files and make an initial commit:
git add -A
git commit -m "first commit"

git add -A: This command stages all changes, including new files, for the next commit.
git commit -m "first commit": This creates a new commit with a commit message "first commit."

### Check repository status and push to GitHub:
git status
git push -u origin main

git status: This command checks the status of your repository after the initial commit.
git push -u origin main: This pushes the committed changes to the remote repository on GitHub, setting up a tracking relationship between the local "main" branch and the remote repository.


### Create a repository on GitHub:
Create a new repository on GitHub (either empty or with a README).

### Connect local and remote repositories:
git remote add origin <repository-url>

git remote add origin <repository-url>: This command connects your local repository to the remote repository on GitHub. Replace <repository-url> with the actual URL of your GitHub repository.

### Push local changes to GitHub:
git push -u origin main

git push -u origin main: This command pushes the local changes to the remote repository on GitHub. The -u flag is used to set up tracking so that you can simply use git push in the future.








git config --global init.defaultBranch main

### creating files and accessing 

touch index.html

git status

git init

ls 

ls -la

git add -A

git commit -m "first commit"

git status

git push 

## create repository on github

git remote add origin (name of the source)

git push -u origin main 



