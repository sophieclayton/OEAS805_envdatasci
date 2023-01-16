# Version control, git and GitHub

## What is version control?
Version control allows you to track changes to a collection of files. This could be code that you are using for your research (e.g. climate models like [MITgcm](https://mitgcm.org/source-code/)), but increasingly version control systems are also being used to track changes and updates to documentation (e.g. [OceanGliders](https://github.com/OceanGlidersCommunity)) and even track the development of manuscripts (e.g. [Overleaf history](https://www.overleaf.com/learn/how-to/Can_I_save_versions_of_my_work%3F), [Google Docs version history](https://support.google.com/a/users/answer/9308971?hl=en)).


![](https://blogs.illinois.edu/files/6397/2138908542/184484.gif)

Version control allows you to:

* see all of the changes made to a project over time (and compare versions)
* see who made which changes to the project
* retrieve previous versions of the project (e.g. commits and/or checkpoints)
* test experimental code features on a separate "branch" before integrating them into the main codebase
* save yourself many headaches and keep your work well organised

## What is git?

![](https://imgs.xkcd.com/comics/git.png)

Git is a local version control tool that tracks changes to projects locally. It is not necessary to have any kind of connection to the internet to use git. Multiple users can use git to collaborate and contribute to projects either by working on the same local system, or by using a service such as GitHub to host the project's repository.

Projects are organised into **repositories** which are really just directories that you tell git to keep track of. Git tracks the changes to files by keeping a record of the changes to the files, called **commits**, rather than saving entire separate versions of the files, which is way more space-efficient. And since git only saves the changes made to files, it is easier to see the differences between versions. As mentione above, git also allows you to create parallel versions of your code, called **branches** to test new features.

## What is GitHub?

[GitHub](http://www.github.com) is an online service that uses git as its core technology and allows distributed users to collaborate on projects remotely. GitHub also allows developers to share projects, track version changes and allow users to check out previous versions of projects, track issues and bugs, host websites, and a bunch more stuff that we won't cover in this course.
