Repository
mkdir <foldername> = make new folder/directory
cd <foldername" = navigate into folder, change directory
ls = list items in a folder
git init = turn Git on for a folder

Commit To It
git status = check status of changes to repository
git diff = view changes to files
git add <filename> = add a file's changes to be committed
git add . = add all files changes
git commit -m "message" = commit changes with message

GitHubbin
git config --global user.username <username> = set Git config username

Remote Control
git remote add <remotename> <url> = add remote connections
git remote set-url <remotename> <url> = set a URL to a remote
git pull <remotename> <branchname> = pull in changes
git remove -v = view remote addresses
git push <remotename> <branch> = push changes to GitHub

Forks & Clones
git clone <url> = clone a fork
cd .. = back out of a directory one level

Branches Aren't Just For Birds
git add -A = commit all changes
git branch -m <newbranchname> = change branch name
git checkout -b <branchname> create & switch to branch
git branch <name> = create branch
git checkout <branchname> = move onto branch
git branch = list Branches

Pull Never Out Of Date
git pull <remotename> <branchname> = pull in changes from a remote branch
git fetch --dry-run = see remote changes before pulling in

Merge Tada
git merge <branchname> = merge branch into current branch
git branch -d <name> = delete local branch
git push <remotename> --delete <branchname> = delete remote branch