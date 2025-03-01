# besant-devops
git remote add origin https://github.com/tharunbyl/besant-devops.git

# download

git pull origin master

git fetch origin master
git merge origin/master

# logs
git log
git log --oneline
git log --oneline --all

git diff <src-hash> <dest-hash>

# ref
https://git-scm.com/doc


# merge
git merge [branch]
git rebase [branch]

# delete
git branch -d [branch]
git branch --delete [branch]

# stash
git stash list
git stash show [stashname]
git stash apply [stashname]
git stash drop [stashname] 
git stash pop [stashname]

# branching strategies

## git flow
    master
      |
      |-------------------------------+
      |                               |
  release/*                        hotfix/*
      |                               |
   develop -------------------------+
      |
  feature/*

## feature branching strategies
   master          release         feature
     |                  |               |
