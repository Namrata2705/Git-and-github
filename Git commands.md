Git is a version control system, where you can track history of a project. It records the changes made to a file, who made the changes and the timestamp.

Commands:

Set gobal Username and Email for git locally:

git config --global user.name "<your username>"
git config --global user.email "<Your Email>"

Initilize an empty git repo:

git init

Clone an existing repository:

git clone <URL>

Add file/stage to git:

git add <FileName>

Add all files to git:

git add .

Commit all staged files to git:

git commit -m "<Your Message>"

Restore the file from being modified to Tracked:

git restore <filename>
git checkout <filename>

Show the status of your Git respository:

git status

Show the branches of your git repository:

git branch

Checkout to a new branch:

git checkout -b <branchname>

Checkout to an existing branch:

git checkout <branchname>

Remove a branch from Git:

git branch -d <branch name>

Show remote origin URL:

git remote -v

Add remote origin URL:

git remote add origin <your remote git URL>

Remove remote origin URL:

git remote remove origin

Fetch all the remote branches:

git fetch

Push your local changes to remote branch:

git push origin <branch name>

Pull your remote changes to local branch:

git pull origin <branch name>

Check you git commits and logs:

git log





