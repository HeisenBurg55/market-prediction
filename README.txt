The application prints "Hello world!".

Remote: https://github.com/HeisenBurg55/market-prediction

Git commands used:
#create market-prediction.py file

git status #check staging/commit status

git add market-prediction.py #add file to staging

git status

#commit from VS Code UI with message "First commit - print Hello world!"

git status

git log #check commit history

#create github repository market-prediction

git remote add origin https://github.com/HeisenBurg55/market-prediction.git #add github repository market-prediction as remote

git remote -v #check remote was added

git branch -a #check branches

git branch -M main #rename 'master' branch to 'main'

git push -u origin main #push changes to remote and set remote as upstream

git checkout -b feature/add-about-project #create feature/add-about-project branch and switch to it

git branch -a #check that I switched to the feature/add-about-project branch

#create appinfo.txt file

git status

git add appinfo.txt

git commit -m 'Add appinfo.txt' appinfo.txt #commit

git log

git checkout main

#change commit message to "Hello world!!!!!"

git status

git add market-prediction.py

git commit -m 'change message to "Hello world!!!!!" ' market-prediction.py

git push origin main

git checkout feature/add-about-project

git pull origin main #failed because of divergent branches

git pull --rebase origin main #pull with rebasing to move feature branch history on top of updated main branch history

git log

git push -u origin feature/add-about-project #create new remote branch feature/add-about-project and set as upstream

#add latest git commands to appinfo.txt and also add the remote link at the beginning

git status

git add appinfo.txt

git commit -m 'add latest git commands to appinfo.txt and also add the remote link at the beginning' appinfo.txt

git log

git push origin feature/add-about-project

git checkout main

#add README.txt with info from appinfo.txt

git status

git add README.txt

git commit -m 'add README.txt with info from appinfo.txt' README.txt

git push origin main

git checkout feature/add-about-project

git pull --rebase origin main #add README.txt to feature branch as well

git push origin feature/add-about-project






