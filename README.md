git init
git remote add origin https://github.com/bulbul-web/clothing.git
git branch --set-upstream-to=origin/master master
git fetch origin
git diff --name-status HEAD origin/master
git pull origin master / git pull
git push origin master / git push
