# Git Commands

**Setting Global User Name**
`git config --global user.name "<USER_NAME>"`

**Setting Global User Email**
`git config --global user.email "<USER_EMAIL>"`

**Create New Git Repository**
`git init`

**Get List of Existing Remotes**
`git remote -v`

### Branches

**View Local Branches**
`git branch`

**Create Branch**
`git branch <NEW_BRANCH_NAME>`

**Switch Branch**
`git checkout <BRANCH_NAME>`

**Create Branch and Switch**
`git checkout -b <NEW_BRANCH_NAME>`

**Update Local Branch from Remote Source**
`git fetch`

**Pull in Remote Branch to Local**
`git pull`

\$ git push # pushes to the remote repository

---

**\*** Committing files **\***

$ git add <file>                                                  # to update what will be committed
$ git checkout -- <file> # to discard changes in working directory

e.g. git add file1 file2 file3

$ git status                                                      # to see what files what is being committed
$ git commit -m "message here" # commits the files

---

**\*** Merging updates into the staging branch **\***

$ git fetch
$ git merge origin/master

---

**\*** Creating a pull request **\***

$ git push <url> <main_branch>
$ git request-pull <url> <main_branch>

e.g.

$ git push https://momentum3.visualstudio.com develop
$ git request-pull https://momentum3.visualstudio.com develop

\$ git request-pull [-p] <start> <url> [<end>]

---

**\*** Push new branch to server **\***

git push -u origin <branch>

---

**\*** Pull remote branch to local branch **\***

$ git branch -r                                                   # lists all remote branches
$ git checkout -b <local-branch-name> origin/<remote-branch-name> # pulls remote branch down to local branch and checks it out

---

**\*** Deleting Remote Branch **\***

\$ git push <remote_name> --delete <branch_name>

**\*** Deleting Local Branch **\***

$ git branch -d <branch_name>
$ git branch -D <branch_name>

---

\$ git --version # get the version of git

---

Add Remote Repository

\$ git remote add origin https://momentum3.visualstudio.com/DefaultCollection/_git/Customer-GCS

---

yarn add bootstrap@4.1.3 --save
yarn add popper.js --save
yarn add sweetalert2 --save
yarn add toastr --save
yarn add moment --save
