mkdir folder  <br>
cd folder <br>
git clone url  <br>


General Stages: 

1) Modify 
2) stage
3) commit
4) push/merge 


echo "# CICD_Steps" >> README.md <br>
git init <br>
git add README.md <br>
git commit -m "first commit" <br>
git branch -M main <br>
git remote add origin https://github.com/sand47/CICD_Steps.git <br>
git push -u origin main <br>


###  pushing to github 

git add . <br>
git commit -m "commit line" <br>
git push <br>

### fetch from github 

git fetch origin  <br>
git merge / git pull  <br>

### before push always pull 

commit first and before push do pull.  <br>
If you see confilt, fix it ->commit and then push <br>

### create branch 

git checkout -b branchName <br>
git push --set-upstream origin branchName <br>
and then push, it will not go to master  <br>

### comeback to master 
git switch branch-name <br>
git checkout master <br>

### removes 

git config --global core.whitespace cr-at-eol

### remove branch 

git branch -d branch_name <br>
git push origin --delete test <br>

### merge request
git status ( to see code that are modified)
git add . 
git commit -m " why push"
git push 


