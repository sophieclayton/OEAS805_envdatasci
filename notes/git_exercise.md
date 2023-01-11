## Git setup and workflow

# Configure git

First check that you have git properly installed on your machine and get it configured. Check the version of git you are running.

```
git --version
```

Now configure git with some global variables, your `user.name` and 'user.email' which should be the same as those used to set up your GitHub account.

```
git config --global user.name "<USER_NAME>"

git config --global user.email "<USER_EMAIL>"
```

Now check that your configuration is what you expect:
```
git config --list
```

# Create your project repository

Now we're going to create a new folder for your project. It's a good idea to keep your file system well organised and so I suggest that you make a separate folder specifically for this class, call it whatever you would like, but avoid using an spaces in your folder or file names. Once you have a folder set up for the class, make a folder in it for this exercise. 

```
mkdir OEAS895

cd OEAS895

mkdir git_exercise

cd git_exercise
```

Now that we have created a directory for this exercise, we can **initiate** it as a git repository.
```
git init
```
You can check whether or not a folder is a git repository by running an 'ls -a' command to list the files in the folder. If your folder contains a '.git' subdirectory, then it is a git repository and changes can be tracked.

For a full list of git commands, use the 'git --help' command to list them in the shell, or use the 'git help everyday' command to get a handy list and explanation of the commands you are most likely to use depending on what your role is in a project.

# Git workflow

Git does not track changes you make to your project automatically. You need to **add** and then **commit** changes to your project as you make them. After your run the 'git add' command on a file that you have changed, you don't have to repeat the filename in the 'git coomit' command, it will commit any files that you have added in the 'git add' step. When you commit changes, you will also add a short text string to explain the changes you have made. Here's an example"
```
git add hello.txt

git commit -m 'wrote hello world text file'
```
You can use 'git log' to print information about your commits to the terminal. If you want to see line by line differences in a 

If you want to create a parallel branch in your repository, then you will use the 'git branch' and 'git checkout' commands. First create a new branch and then check which branch your are working in:
```
git checkout -b new_branch

git branch
```
Once you have made changes in the new branch, tested them and decided that you want to incorporate them into the main branch of the project, you'll run a 'git merge' command:
```
git checkout main

git merge new_branch
```




  
