
## Learn Git & Github in 10 minutes

## GIT

- __Git__ is a free and open-source distributed version control system used for tracking changes Locally (i.e.) within our Machine.

## Github

- __GitHub__ is a code hosting platform for version control and collaboration. 

## .gitignore

- Creating a __.gitignore__ file it tells Git to ignore specified files and directories while doing a commit. 

## Git Pull vs Git Fetch

- __Git Pull__ command will get Latest changes from Central Repository to Local Repository(i.e.) File Transfer will happen here.
- __Git fetch__ is a safer alternative because it pulls in all the commits from your remote but doesn't make any changes to your local files.

## Git Merge vs Git Fetch

- __Git Merge__ and __Git Rebase__ are both used to combine the changes of branches but in a distinct way.
- __Git merge__ is used to integrate changes from another branch.
- __Git Rebase__ rebase takes your entire feature branch and moves it to the tip of the main branch.


## Commands

| Commands	 | Descriptions |
| --------	 | ------------ |  
| git init	| For creating local repository. |
| git add .	| For adding entire files in staging. |
| git status	| To get the status. |
| git commit -m "'Commit Description'"	| For commiting all local changes in Git. |
| git log	| Changes that we have done. |
| git remote add origin 'Remote URL'	| For Adding the Remote URL from the GitHub. |
| git pull origin 'Branch Name' --allow-unrelated-histories	| Do an Intial Pull before pushing the File to Remote. |
| git commit -m "'Commit Description'"	| For commiting all local changes in Git. |
| git push -u origin 'Branch Name' | For pushing the Local Repository Files to Remote. |
| git clone 'Remote URL' | To Download the Repository from the Remote URL by making a Copy. |
| git branch 'branch_name' | To Create the new Branch. | 
| git branch | To Show the List of Branches. |
| git checkout 'branch_name' | Move from One branch to Aother branch. |  
| git merge 'branch_name' | Move from One branch to Aother branch. |
