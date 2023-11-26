# This is Some of The Most Important Git Commands

**git clone 'link'** : *Clones The Repository With The Link*.
**git status** : *gives you the status of your branch (untracked,commited,renamed,deleted,added ...)*.
**git add 'FileName'** : *Adds The New File To The Stage*.
**git restore --staged 'FileName'** : *Unstages The 'FileName' File*.
**git clean -n** : *shows the files that would be removed.(unstaged files).*
**git clean -f** : *Removes all Unstaged Files.*
**git commit -m "Note"** : *Commits The Added File Along With a Note*.
**git branch** : *Shows The Available Branches*.
**git branch 'branchName'** : *Creates the branch 'branchName'*.
**git checkout 'branchName'** : *Switches to The 'branchName'*.
**git checkout -b 'branchName'** : *Creates The Branch and Switches to it*.
**git branch -d 'branchName'** : *Delets The Branch 'branchName' if it doesn't contains any changes.*
**git branch -D 'branchName'** : *Delets The Branch 'branchName' No Matter What.*
**git remote** : *Gives The Remote Name.*
**git push 'Remote' 'Branch'** : Pushes The Commited Files From The Branch To The Remote.
**git pull 'Remote'** : Pulls The Changes Made Within The GitHub Into The Cloned Repository.
**git push -u 'Remote' 'Branch'** : Pulls Before Pushing. (Recommended).
**git merge 'branchName'** : Merges The Current branch with the branch 'branchName'.
**git config -l** : Gives a List Of All The Available Git Configurations.
**git help config** : Opens The Git Configuration Manual.
**git config --global 'config.exp'** : Gives The Config.exp Value.
**git config --global 'config.exp' 'NewValue'** : Sets The Config.exp To The NewValue You've Wrote.
**git config --global --unset 'config.exp'** : Unsets The Config.ext.
**git config --global --edit** : Opens The Editer To Edit Configurations From it.
**ssh-keygen -t rsa -b 4096 -C "email"** :  creates a key generator for the user of the email.
**git init** : creates a git repository from your current directory. It adds .git folder inside of it.
**git init --bare** : also creates a repository, but it does not have the working directory. This means that you can not edit files, commit your changes, add new files in that repository.
**git remote add origin "ssh link"** : Transfers The Repo To The Remote.
**git branch -M 'NewName'** : changes the branch name to the NewName.
**git config --global alias.New 'command'** : sets the alias of 'command' to 'New'.
**git config --global alias.New** : gets the command of alias 'New'.
**git log --oneline** : displays your commits as single lines for more compact output.
**git log -1 HEAD --stat** : Use it to see the last commit.
**git config --global -l** : lists all user configuration.
**git config --global help.autocorrect 20** : enables autocorrecting commands.
**git stash** : takes your uncommitted changes (both staged and unstaged), saves them away for later use.
**git stash save "Note"** : saves the stash with a message.
**git stash list** : pulls up a list of all the changes you've stashed.
**git stash show** : shows the files of the latest stash, use (stash@{index})to specify the stash,example : "git stash show stash@{2}" ==> shows the stash indexed by 2.
**git stash pop** : pops the latest stashed changes into the working directory, use (stash@{index})to specify the stash.
**git stash apply** : copies the latest stashed changes into the working directory, use (stash@{index})to specify the stash.
**git stash branch 'branchName'** : This command creates a new branch with the latest stash, and then deletes the latest stash ( like stash pop), use (git stash branch 'branchName' stash@{index}) to specify what stash.
**git stash drop** : delets the latest stashed changes, use (stash@{index})to specify the stash.
**git stash clear** : clears all the stashes.
**git log** : shows the commit logs.
**git reset --hard 'commit's SHA'** : points the Head to the specefied commit, by doing that it delets every commit that have been commited after it.
**git reset --soft 'commit's SHA'** : Will point the Head to the specified commit, and have all the changes in the proceeding commits, returned as staged.
**git tag** : Lists the existing tags in Git.
**git tag 'tag version : v1.0'** : Creates a Lightweight Tag, a Lightweight Tag is just a pointer to a specific commit.
**git tag -a 'TagName' -m 'Tag Message'** : Creates an Annotated Tag, Annotated tags are stored as full objects in the Git database. To reiterate, They store extra meta data such as: the tagger name, email, and date. Similar to commits and commit messages Annotated tags have a tagging message.
**git push 'remote' 'tag name'** : pushes the version to the remote.
**git tag -d 'tag name'** : Delets The Tag From The Branch.
**git push origin --delete 'tag'** : Delets The Tag From The Remote.
**git config --get-regexp alias** : Checks All Aliases That You're Using.
**git config --global --remove-section alias** : Removes All Aliases.
