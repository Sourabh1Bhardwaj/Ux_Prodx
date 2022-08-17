git init 
touch index.html
git add index.html
touch bluestack.css
git add bluestack.css
git commit -a -m "add files"
git branch hello-world-images
git branch
git checkout hello-world-images
git merge hello-world-images
git remote add origin https://github.com/Sourabh1Bhardwaj/Ux_Prodx
git push --set-upstream origin master

//pull is a combination of 2 different commands:
1.fetch
2.merge

git fetch origin
git log origin/master
git diff origin/master
git merge origin/master
