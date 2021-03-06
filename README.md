#Practice repository for GIT

## Commands used

- git init: Create a repository
- git status: Compare working directory, staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show history of project commits

- git remote add remote url: Add a new <remote> at url
- git remote -v: List remote repositories
- git push -u remote branch: Push <branch> to remote, and set default upstream for branch
- git fetch: Fetch changes from remote repository
- git pull:  Fetch and then merge


## Commit messages

Default editor is vim (this can be changed)
  - 'i' to enter *insert* mode
  - Type commit message
  - 'Esc' -> 'wq' -> 'Enter' to write message and quit
  Or use git commit -m "<message>"

  - First line should be clear, accurate, and concise
  - Use proper spelling, grammar and punctuation
  - Don't end with a '.'

  for more advise, see https://chris.beams.io./posts/git-commit/

  ## What's a remote?

  A remote repo is one hosted somewhere other than our local
  machine.  We can add remotes with 'git remote add', and set up *tracking branches* to track differences between our local and remote repositories.

  We push to remotes with 'git push' and fetch from them with 'git fetch'.  We can also fetch and merge in one set with 'git pull'.
