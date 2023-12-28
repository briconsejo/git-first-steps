# Git First steps exercises

## Preparation.

1. Ensure git is available
```
git help -a
```
2. Make a fork of your repo.

## Normal operation: Add new telephone

1. Clone this repo with
 ```git clone <your forked repo>```

2. Edit phone list file and add a new number. Then add the change to the staging area.
```
git add --help
git add phone_numbers.txt
```

3. Add a new phone to the list, and this time use `git add -a` to add it.
```
git add -p
```

4. Commit the changes
```
git commit -m "I just added two new phone numbers"
```


5. Push the commit to github
```
git push
```

## Branch Operation: make changes via manual merge and push

1. switch to a NEW branch (`-b` param )
```
git checkout -b mybranch
```

1. Edit phone list file and add a new number. Then add the change to the staging area.
```
git add -p
```

4. Commit the changes
```
git commit -m "I just added a new phone number"
```

5. Merge changes into main branch.
```
git checkout main
git merge mybranch
```

6. View git log
```
git log
```

## Pull Request Operation: make changes via manual merge and push

1. switch to a NEW branch (`-b` param )
```
git checkout -b mybranch
```

1. Edit phone list file and add a new number. Then add the change to the staging area.
```
git add -p
```

4. Commit the changes
```
git commit -m "I just added a new phone number"
```

5. Open a PR in github.



