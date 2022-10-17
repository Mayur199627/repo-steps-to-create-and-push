# creating a repo:-
1. Click on repo or new repo.
2. write your repo name.
3. click on create repository.

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
9. commit all the changes to current branch.
# git commit -m "message"
10. Push all the changes to the current branch.
# git push origin master

# pushing the new changes to current repo.
1. stage all the changes.
# git add .

2. commit all the changes.
# git commit -m "Change readme.md"

3. pushing all the changes.
# git push origin master