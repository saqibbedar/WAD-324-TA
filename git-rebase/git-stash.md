# git stash

```bash
# saves all tracked modified & staged work
git stash #OR git stash push 

# Saves a stash with a custom description
git stash push -m "message"

# saves untracked new files alongside tracked changes
git stash push -u       # -u: --include-untracked

# Includes all files, including untracked files and files listed in .gitignore
git stash push -a       # -a: all

# Stashes only the specified file or directory, add -u if you want to include -untracked files
git stash push -- path/to/file

# multiple files or dirs
git stash push -u -m "Save temp assets" -- assets/icons/ utils/helper.js

# applies to top of the stack and pop it
git stash pop

# remove by index
git stash pop stash@{2}

# permanently delete all saved stashes in the repository
git stash clear
```

