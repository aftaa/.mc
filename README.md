cd ~/.config/mc

git init

git remote add origin git@github.com:aftaa/.mc.git

git pull origin master

git branch --set-upstream-to=origin/master master
