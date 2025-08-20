# Gym-Git-Exercise-Solutions

# Bundle 1 exercise 1

git init
git branch -m main
git checkout -b dev
git checkout -b test
git branch -d test
git add .
git commit -m "initial commits and delete the test branch"
git push origin dev`


# Bundle 1 exercise 2
```
PS D:\hands-on practice\The Gym\Git-exercise> git add .
PS D:\hands-on practice\The Gym\Git-exercise> git stash list
PS D:\hands-on practice\The Gym\Git-exercise> git status

PS D:\hands-on practice\The Gym\Git-exercise> git stash
Saved working directory and index state WIP on main: df9f2cd initial commits and delete the test branch

PS D:\hands-on practice\The Gym\Git-exercise> git add about.html
PS D:\hands-on practice\The Gym\Git-exercise> git stash
Saved working directory and index state WIP on main: df9f2cd initial commits and delete the test branch
PS D:\hands-on practice\The Gym\Git-exercise> git add team.html
PS D:\hands-on practice\The Gym\Git-exercise> git stash
Saved working directory and index state WIP on main: df9f2cd initial commits and delete the test branch
PS D:\hands-on practice\The Gym\Git-exercise> git stash list

PS D:\hands-on practice\The Gym\Git-exercise> git stash apply "stash@{1}"
PS D:\hands-on practice\The Gym\Git-exercise> git stash apply "stash@{2}"

PS D:\hands-on practice\The Gym\Git-exercise> git add .
PS D:\hands-on practice\The Gym\Git-exercise> git commit -m "stash files home and about.html"

PS D:\hands-on practice\The Gym\Git-exercise> git push origin  main

PS D:\hands-on practice\The Gym\Git-exercise> git stash pop "stash@{0}"
PS D:\hands-on practice\The Gym\Git-exercise> git reset --hard
 ```

# Bundle 2 exercise 1

```
git checkout -b ft/bundle-2
git add .
git commit -m "ft: service page inital commit"
git push origin main ft/bundle-2
```

# Bundle 2 exercise 2

```
git checkout main
git pull origin main
git checkout -b ft/service-redesign
git add .
git commit -m "add services we offer"
git push orifin ft/service-redesign
git diff ft/service-redesign main
git pull origin main
git switch  main
git commit -m "fix the conflicts"
git push origin main
```

# Bundle 3 exercise 1

```
git checkout main
git checkout -b ft/team-page
git add .
git commit -m "add Team members"
git revert 65bddc1
```

# Bundle 3 exercise 2

```
git checkout -b ft/home-page-redesign
git switch main
git pull origin main
git rebase main
```