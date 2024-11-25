The application prints "Hello world!".

Remote: https://github.com/HeisenBurg55/market-prediction

#created github repository market-prediction

#opened VS Code market-prediction folder

git init

git remote add origin https://github.com/HeisenBurg55/market-prediction.git #add github repository market-prediction as remote

git remote -v #check remote was added

git branch -M main #rename 'master' branch to 'main'

#created market-prediction.py file

git status #check staging/commit status

git add market-prediction.py #add file to staging

git commit -m 'add market-prediction.py' market-prediction.py #commit to main branch

git status

git push -u origin main #push changes to remote and set remote as upstream

git checkout -b feature/add-about-project #create feature/add-about-project branch and switch to it

git branch -a #check branches

#created appinfo.txt file

git status

git add appinfo.txt

git commit -m 'Add appinfo.txt' appinfo.txt 

git log #check commit history

git checkout main

git branch -a

#added README.md with info about git commands used for this project

git status

git add README.md

git commit -m 'add README.md' README.md

git push origin main

git checkout feature/add-about-project

git branch -a

git pull origin main #failed because of divergent branches, I have to choose merge or rebase

git merge origin main

git log

git status



