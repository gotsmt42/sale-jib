git remote remove origin
git remote -v

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/gotsmt42/[repository]
git push -u origin main

git add -A
git commit -m "new update"
git push -u origin [branch]

git fetch 
git merge origin/[branch]
git pull 

git branch -b [create-branch-name] //สร้าง branch พร้อม เปลี่ยน branch
git branch [create-branch-name]
git branch -d [detete-branch-name]

git checkout [branch-name] /เปลี่ยน branch

git status

