mkdir folder 
cd folder 
git clone url 
put file 

1) Modify 
2) stage
3) commit
4) push 


echo "# CICD_Steps" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sand47/CICD_Steps.git
git push -u origin main


# pushing to github 

git add .
git commit -m "commit line"
git push 

# fetch from github 

git fetch origin 
git merge / git pull 

# before push always pull 

commit first and before push do pull. 
If you see confilt, fix it ->commit and then push 

# create branch 

git checkout -b branchName
git push --set-upstream origin divbranch
and then push, it will not go to master 

# comeback to master 
git switch branch-name
git checkout master 

