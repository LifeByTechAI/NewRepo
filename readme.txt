Notes: 

Creatinga  new directory: 
git mkdir

Staging: 
git add file.name 

Comitting: 
git commit file.name

Commit without staging: 
git commit -a -m "Note to save wiith" 

Checking Status: 
git status

Branch: 
git branch // lists the name of the branches
git branch Name 

Switching in between branches: 
git checkout branchName
git branch // list

Different Git Session running: 
rm -f .git/index.lock

Emergency Branch: 
git checkout -b emergency-fix
// Creates an emergency branch

Merging branches to the new branches: 
1) Switch to the master branch 
2) merge the branch by using the command "git merge emergency-fix"
3) Then delete the old branch " 

Review Branch Status

Adding a new branch 
- git remote add origin "name of the branch" 

- git push --set-upstream origin master (this command pushes the repo to the cloud)

Pulling from GitHub: 
- pull (option to do either fetch or merge)

fetch: Gets all of the changes for the branch 
merge: Will push all of the changes to merge 

Pushing to github: 
- Push: meaning pushing your local repositity to github. 

GitHub: 
- Study GitHub flow, theoritical 
Notes: you can host your entire website on GitHub! 

new
