# Creating a repo:-
1. Click on repo or new repo.
2. Write your repo name.
3. Click on create repository.

# Making project on repo :-
1. goto your terminal or
# ctrl + shft + `
2. initialize your git.
# git init
3. Configure the user.
# git config --global user.name
# git config --global user.name "user name"
# git config --global user.email
# git config --global user.email "email id"

Note :- stap 1 to 6 is for first time installation or configartaion. After first time we have to direct start from stap7  
7. Add the remote git origin / Add your repo.
# git remote add origin paste link of repo
8. Add all the changes to stage. To tell the git that this are the changes we have to commit.
# git add . or . else file name
9. Commit all the changes to current branch.
# git commit -m "message"
10. Push all the changes to the current branch.
# git push origin master

# Pushing the new changes to current repo.
1. Stage all the changes.
# git add .

2. Commit all the changes.
# git commit -m "Message"

3. Pushing all the changes.
# git push origin master

# Creating github pages
1. Go to your github repository.
    Requirnment:-
    a. You should have only one index.html file in root of the folder.

2. Go to settings.
3. Open The pages from left sidebar.
4. Select option as Deploy from branch.
5. Select your branch as master /main.
6. Click on save botton.
7. Wait for 5 min ans reload page.
8. Click on visit site.

# Getting the repository changes to local system.
1. Pull from repo.
# git pull origin master

# Creating new branch in github.
# git chechout -b "new-Branch"

GSSOC : Google summer school of code

# Delete file from git hub
1. Delete file from local host.
2. git add .
3. git commit -m "delete file"
4. git push origin master