echo "# SAtest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/NACHATx69/SAtest.git
git push -u origin main

update
git checkout -b dev/#0001-feature
git add -u
git commit -m "My feature is ready"
git push origin dev/#0001-feature

merge
git checkout main
git merge dev/#0001-feature