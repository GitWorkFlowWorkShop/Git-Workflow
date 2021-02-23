# Git

Git Workflow 

## Abstract

1. Create an oranization.
2. Create a project inside the organization.
3. If the project is private you need to add all the collaborators.
4. Each collaborator has to fork to the machine.
5. Every developer has to clone their project to their machine.
6. The programmer has to add the remotes of the original project.
7. It must make sure that everything is correctly synced.
8. A new branch will be created to work with a feature.
9. Once the work is done, the developer pushes his changes to his fork.
10. On Github will show up an option to create a pull request.
11. Once the pull request is created the project manager will check it out.
12. The pull request either is rejected or approved.
13. Every developer has to check constantly if there were any changes to the original project.
14. The branches that were approved or rejected must be eliminated

## Organization

It is recommended to create a new organization that is the owner of the main repository.Starting with this repository all the collaborators and members will do a fork to their accounts

### Steps to create an organitation on GitHub

1. Click on your profile photo
2. Click on settings
3. Click on organitation (Left menu)
4. Click on new organitation
3. Choose the plan and fill up data

### Create a fork

For creating a fork you must sign in on Github and then go to the landing page's project of whatever fork you want to do. 

## Working with remotes repositores

Display remotes repositories
` git remote -v`

Add a remote repository
`git remote add {name} {URL}`

Delete a remote link
`git remote remove {Name}`


## Creating tags

It is neccesary to understand that the tags only have to be created on the master branch as a good practice.

To understand how to name or set up your new versions we recommend you an article on out blog: https://ed.team/blog/como-se-deciden-las-versiones-del-software
