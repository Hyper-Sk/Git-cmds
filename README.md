
************** deploy html pages : *******************

1. create repo on the github then copy repo URL 
2. clone the project by following repo URL in the file editor

3. after editing or adding files : 
	git add .

4. git status : to check the status.
5. git commit -m 'update name' 
6. git push 



*********** deploy react website on github (react pages) : - ************


1. npm install gh-pages --save-dev

2. open github create new repo 

3. git initialization on react project : 
    git init
    git add README.md 
    git add .
    check status :
        git status
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/username/reponame.git
    git push -u origin main


4. open package.json file and add following key pare :
    "homepage": "https://username.github.io/reponame"

5. open package.json file and add following key pare in the "script" :
    "predeploy":"npm run build"
    "deploy" : "gh-pages -d build"

6. npm run deploy

7. go to repo setting then pages you see link open-> 



************* Update React Pages : ****************


1.  git add .
    check status :
        git status
    git commit -m "changed colors"
    git branch -M main
    git push -u origin main

2. npm run deploy





************* git remote commands ****************** 

check remote origin :
	git remote -v

delete remote origin :
	git remote remove origin // it'll delete all origins

add remote origin : 
	git remote add origin URL 




