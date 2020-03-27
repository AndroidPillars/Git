# Git

- Git is an Open Source Distributed Version Control System tool designed to handle everything from small to very large projects 
with speed and efficiency.

# Version Control System

- Version Control System is a system to track changes in file(s) by making a version snapshot changes of that particular file over time.
- The various types of the version control systems are,
  1. Local Version Control System
  2. Centralized Version Control System
  3. Distributed Version Control System

# Local Version Control System

- Local version control system maintains track of files within the local system.
- This approach is very common and simple.
- This type is also error prone which means the chances of accidentally writing to the wrong file is higher.

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77502263-60601400-6e80-11ea-97a6-ce034c75a82e.png"/>
</p>

# Centralized Version Control System

- In this approach, all the changes in the files are tracked under the centralized server.
- The centralized server includes all the information of versioned files, and list of clients that check out files from that central place.  
Example: Tortoise SVN

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77503128-e67d5a00-6e82-11ea-8bd7-48be2c3c6b94.png"/>
</p>

# Distributed Version Control System:

- Git has a remote repository which is stored in a server and a local repository which is stored in the computer of each developer.
- This means that the code is not just stored in a central server, but the full copy of the code is present in all the developers’ computers. 
- Git is a Distributed Version Control System since the code is present in every developer’s computer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77503779-7c65b480-6e84-11ea-863d-8231e889fe5f.png"/>
</p>

# Git Installation

- https://git-scm.com/
- Install Git -> Select Folder -> Right Click Mouse -> Choose Git Bash Here

# How it Works

- Working Directory (File) -> git add -> Staging Area(File) -> git commit -> Local Repository.

# Commands

| Commands	 | Descriptions |
| --------	 | ------------ |
| cd Desktop |	Opens <b>Desktop</b> |
| mkdir Story	| Creates the <b>Story</b> Folder. |
| cd Story | Opens the <b>Story</b> Folder. |
| ls | To List the Files in the Folder. |
| touch Sample.txt	| For creating the <b>Sample.txt</b> file. |
| open Sample.txt	| For Opening the <b>Sample.txt</b> fle. |
| vim Sample.txt	| For Editing the <b>Sample.txt</b> file using vim editor. |
| rm -rf Sample.txt	| For deleting the <b>Sample.txt</b> file. |
| rmdir Story	| For deleting the <b>Story</b> folder. |
| ls -a	| To find the hidden files. |
| git init	| For creating local repository. |
| git status	| To get the status. |
| git add Sample.txt	| For adding the git files in staging. |
| git commit -m 'Intial Commit'	| For commiting One.txt in Git Repository. |
| git commit -a -m 'Intial Commit'	| For commiting Entire Files in Git Repository. |
| git log	| Changes that we have done. |
| git log --oneline	| For getting the Changes in one line. |
| git add .	| For entirely adding all files in Git Repository. |
| cd ..	| To navigate to the Git main folder. |
| clear |	To clear all. |
| git --version	| For version check. |
| git rm -- cached Sample.txt	| For removing that in Git Repository. |
| git diff	| To find the changes done in the directory. |
| touch .gitignore	| To ignore the files in Git Repository. |
| git config user.name 'Gowtham'	| For setting the Author name. |
| git config user.email 'gowtham@gmail.com'	| For setting the Author email. |
| cat Sample.txt	| It reads data from file name and the content as output. |
| git checkout	| To revert back to the last version. |
| rm -rf .git	| To remove all the repository expect working directory. |

# GitHub Installation and setup

- Create the Account in https://github.com
- Create New Repository.
- To set up Repository we can use Desktop or by using command line.
- We have to push an existing repository to the Remote Repository.
- For that, We have to copy the address of the GitHub Repository.
- Then We have to push an existing repository by using the command line (i.e) Project path -> Cmd Prompt
```ruby
git remote add origin https://github.com/AndroidPillars/Git-and-GitHub.git
git push -u origin master
```
- where, https://github.com/AndroidPillars/Git-and-GitHub.git -> Is the path where we copied from Remote Repository and git push -u origin(Name of Remote) master(Name of Branch) -> It pushes the Local Repository to the Remote Repository.

# Common Issues

- warning: unable to access '/Users/username/.config/git/ignore': Permission denied

```ruby
sudo chown -R username /Users/username
```

# Reference Sites

- https://medium.com/@kamilmasyhur/what-do-you-know-about-version-control-system-vcs-6a1e1922c970
- https://blog.eduonix.com/software-development/learn-three-types-version-control-systems/
- https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/
