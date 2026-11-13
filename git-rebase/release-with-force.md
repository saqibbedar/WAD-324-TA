# --force-with-lease

`git push --force-with-lease` is a safer alternative to `git push --force` that lets you overwrite remote commit history only if no one else has pushed new changes to the remote branch since your last fetch. If the remote branch has unseen commits, the push fails rather than erasing your teammates' work.