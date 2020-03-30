# Topics

| S.No | Content |
| --------	 | ------------ |
| 1 | [Git](README.md#git) |
| 2 | [Version Control System](README.md#version-control-system) |
| 3 | [Local Version Control System](README.md#local-version-control-system) |
| 4 | [Centralized Version Control System](README.md#centralized-version-control-system) |
| 5 | [Distributed Version Control System](README.md#distributed-version-control-system) |
| 6 | [Git Installation](README.md#git-installation) |
| 7 | [Commands](README.md#commands) |
| 8 | [GitHub Installation and setup](README.md#github-installation-and-setup) |
| 9 | [.gitignore](README.md#gitignore) |
| 10 | [Clonning](README.md#clonning) |
| 11 | [Branching and Merging](README.md#branching-and-merging) |
| 1 | [Git](README.md#git) |
| 1 | [Git](README.md#git) |



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

# Distributed Version Control System

- Git has a remote repository which is stored in a server and a local repository which is stored in the computer of each developer.
- This means that the code is not just stored in a central server, but the full copy of the code is present in all the developers’ computers. 
- Git is a Distributed Version Control System since the code is present in every developer’s computer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77503779-7c65b480-6e84-11ea-863d-8231e889fe5f.png"/>
</p>

# Git Installation

- Visit, https://git-scm.com/
- Install Git -> Select Folder -> Right Click Mouse -> Choose Git Bash Here

# How it Works

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77731188-73ade380-7028-11ea-90ef-20dee9f175d3.png"/>
</p>

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
| git add Sample.txt	| For adding <b>Sample.txt</b> git file in staging. |
| git add .	| For adding entire files in staging. |
| git commit -m 'Intial Commit'	| For commiting all local changes in Git. |
| git log	| Changes that we have done. |
| git log --oneline	| For getting the Changes in one line. |
| cd ..	| To navigate to the Git main folder. |
| clear |	To clear all. |
| git --version	| For version check. |
| git rm --cached Sample.txt	| For removing <b>Sample.txt</b> in Git. |
| git diff	| To find the changes done in the directory. |
| touch .gitignore	| To ignore the files in Git. |
| git config user.name 'YourName'	| For setting the Author name. |
| git config user.email 'YourMail@gmail.com'	| For setting the Author email. |
| cat Sample.txt	| It reads data from <b>Sample.txt</b> and the content as output. |
| git checkout sample.txt| To revert back <b>sample.txt</b> to the previous version. |
| git rm --cached -r .| To remove everything inside current directory of the staging area. |
| rm -rf .git	| To remove all the repository expect working directory. |

# GitHub Installation and setup

- Create an Account in https://github.com
- Create New Repository.
- To set up Repository we can use either Desktop or by using command line.
- We have to push an existing repository to the Remote Repository.
- For that, We have to copy the address of the GitHub Repository by clicking clone or download button.
- We have to push an existing repository by using the command line (i.e) Project path -> Cmd Prompt  
  ```ruby
  {empty} +
  git remote add origin https://github.com/AndroidPillars/Story.git
  git push -u origin master
  ```
  <b>where</b>,  https://github.com/AndroidPillars/Story.git is the path where we copied from Remote Repository and 
git push -u origin(Name of Remote) master(Name of Branch) it pushes the Local Repository to the Remote Repository.

# How it Works

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77735454-98a65480-7030-11ea-957a-7a41c11e5636.png"/>
</p>

# .gitignore

- You can create a .gitignore file in your repository's root directory to tell Git which files and directories to ignore when you make a commit. 
- Open Terminal.
- Navigate to the location of your Git repository.
- Create a .gitignore file for your repository.

```ruby
$ touch .gitignore
```
<b>For Example</b>,
- If you exclude files or folders just enter their names in .gitignore file.
```ruby
Sample.txt
```
- If you wanna exclude all files ending in .log,
```ruby
*.log
```
# Clonning

- Open https://github.com
- Choose the project you want to clone.
- Click the Clone or download button.
- Copy the URL
- Now, In your machine open command prompt and type,
```ruby
git clone https://github.com/AndroidPillars/Story.git
```
<b>where</b>, 
- https://github.com/AndroidPillars/Story.git is the url you copied in Github.
- Also, you can check the git commit using,
```ruby
git log
```

# How it Works

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77751410-a74e3500-704b-11ea-832b-079c272ff37b.png"/>
</p>

# Branching and Merging

- The Branch allows you create another line of development.
- We can use this Branch to fork off the development process into two different directions by creating multiple branches.
- The default branch name in Git is master.  
<b>For Example,</b> 
- If we are creating a new feature in the current working Application instead of continuing to commit to the master branch we can also create a side branch as experimental branch. So now we have two branches that are parallel to each other and they can developed simultaneously.
- Now, if at some point in the future, we decide to merge the experimental branch to the master branch then it will be done simply placing a mergerequest in by checking any conflict is there with the main branch code.

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77848716-6fc6c080-71e4-11ea-93fd-c360270578ee.png"/>
</p>

<b>For Creating New Branch in Git</b>,
```ruby
git branch branch-one
```
<b>Where</b>,
- branch-one is the Branch Name.

<b>For Checking the Current Branch</b>,
```ruby
git branch
```
- The asterisk shows the current Branch.

<b>We can Switch from One Branch to Other Branch</b>,
```ruby
git checkout branch-one
```
<b>Where</b>,
- git checkout branch-one mentions that, we are Switching from master Branch to branch-one Branch.

<b>For Merging from Other Branch to the master Branch</b>,
```ruby
git merge First-Branch
```
<b>Where</b>,
- git merge First-Branch mentions that, we are merging the files from branch-one Branch to master Branch.

<b>For Creating New Branch in Github</b>,
- Click <b>Branch: master</b> in the Github project Repository where you can create other Branch.
- In the new brach you can either create or Edit the Files or Folders.
- Then, you have to click the <b>Commit Changes</b> button at the Bottom by giving the proper comments.
- Once you get commited you will find New pull request and  Compare & pull request button.

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77762282-4a5c7a00-705f-11ea-8176-06b0e654114c.png"/>
</p>

- Click either New pull request and  Compare & pull request button.
- Now you make the base as master and in compare choose the branch that you have made changes.
- You compare the changes you have done and click Create pull request button.
- Go on to the pull request tab and  check the changes that you have done.

<p align="center">
 <img src="https://user-images.githubusercontent.com/48873155/77848396-fded7780-71e1-11ea-8865-530f65d80241.png"/>
</p>

- Finally click the Merge pull request button.


# Common Issues

- <b>In Mac,</b> Warning: unable to access '/Users/username/.config/git/ignore': Permission denied

```ruby
sudo chown -R username /Users/username
```

# Reference Sites

- https://medium.com/@kamilmasyhur/what-do-you-know-about-version-control-system-vcs-6a1e1922c970
- https://blog.eduonix.com/software-development/learn-three-types-version-control-systems/
- https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/
- https://github.com/github/gitignore
