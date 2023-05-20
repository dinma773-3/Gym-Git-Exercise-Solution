# Gym-Git-Exercise-Solution
# Project
# Bundle 1
   # Exercise 1
   1  mkdir project
   2  cd project
   3  git branch
   4  ls
   5  git init
   6  git branch
   7  git branch -m master main
   9  vi 1-index.html
   10  git add .
   11 ls
   12  git commit -m "new"
   13   git config --global user.email "godsfavourchukwudi21@gmail.com"
   14  git config --global user
   15  git config --global user.name "dinma773-3
   16  git config --global user.name "dinma773-3"
   17  git commit -m "new"
   18  git push
   19  git remote https://github.com/dinma773-3/Gym-Git-Exercise-Solution.git
   20  ls
   21  git remote add origin https://github.com/dinma773-3/Gym-Git-Exercise-Solution.git
   22  git push -u origin main
   23  git branch dev
   24  git checkout dev
   25  git branch -b test
   26  git branch test
   27  git checkout test
   28  git checkout dev
   29  git branch -d test
   
   # exercise 2
   1 vi home.html
   2  git stash save
   3  git status
   4  git add .
   5  git stash save
   6  vi about.html
   7  git add .
   8  git stash save
   9  vi team.html
   10  git add .
   11  git stash save
   12  git stash
   13  git stash list
   14  git stash pop stash@{2}
   15  git stash pop stash@{0}
   16  ls
   17  git stash save team.html
   18  git stash list
   19  git stash pop stash@{1}
   20  git commit -m "new"
   21  git push
   22  git stash pop stash@{1}
   23  git stash pop stash@{0}
   24  git reset HEAD~0
   25  ls
   26  git reset HEAD~1
   27  ls
   28  git history
   29  history
# Bunde 2
  # Exercise 1
  1  git checkout -b ft/bundle-2
  2  vi services.html
  3  git add services.html
  4  git commit -m "new"
  5  git push origin ft/bundle-2
  6  git checkout main
  7  git pull
  # Exercise 2
  1  git checkout -b ft/service-redesign
  2  ls
  3  vi services.html
  4  git add service.html
  5  mv services.html service.html
  6  ls
  7  git add service.html
  8  git commit -m "new"
  9  git push origin ft/service-redesign
  10  git checkout main
  11  vi service.html
  12  git pull
  13  ls
  14  vi service.html
  15  git add service.html
  16  git commit -m "new"
  17  git push origin main
  18  git pull
  19  git checkout ft/service-redesign
  20  git checkout ft/service-redesign
  21  git status
  22  vi service.html
  23  git add service.html
  24  git commit -m "resolved"
  25  git push origin
  26  git pull
  27  vi service.html
  28  git commit -m "resolved"
  29  vi service.html
  30  git add service.html
  31  git commit -m "resolved"
  32  git push origin main
  33  git merge ft/service-redesign
  34  history

