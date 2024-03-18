### Git init :- 
* `git init` is a command in Git, a version control system, that initializes a new Git repository in the current directory or in the directory specified. Git creates a new subdirectory named ".git" in the current directory after running the `git init` command.
```sh
git init
(or)
git init < YOUR REPOSITORY PATH >
```
 !["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/img1.png "Optional Title")

 ### Git Clone :-
* The `git clone` command is used to create a copy of an existing Git repository. When you run `git clone`, you're essentially making a duplicate of a repository, including all its files, commit history, and branches.
```sh
git clone <GIT REPOSITORY URL>
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/img2.png "Optional Title")

### Git Add :-
* The `git add` command is used to tell Git to start tracking new files or changes to existing files in your project. Git adds these files or changes to what's called the "staging area."
```sh
git add <FILE NAME>
(or)
git add .        //to add all the files
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/img3.png "Optional Title")

### Git Status :-
* The `git status` command is used to get information about the current state of your Git repository. When you run `git status`, Git provides you with details about
  * Which files have been modified since the last commit.
  * Which files are staged and ready to be committed.
  * Which files are untracked (new files that Git isn't keeping track of yet).
  * The current branch you're on.
```sh
git status
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/img4.png "Optional Title")

### Git Commit :-
* The git commit command is used to save your changes to the Git repository. When you run git commit, you're creating a snapshot of the changes you've made since the last commit. Git will prompt you to write a commit message, describing the changes you've made.
```sh
git commit -m "YOUR COMMIT MESSAGE"
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/git%20commit.png "Optional Title")

### Git Push :-
* The `git push` command is used to push the commits from local repository to remote repository.
```sh
git push origin <BRANCH NAME>

git push -all        //to push into all branches
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/git%20push.png "Optional Title")

### Git rm :-
* The `git rm` command is used to remove files from your Git repository.
```sh
git rm <FILE NAME>
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/git%20remove.png "Optional Title")

### Git log :-
* The `git log` command is used to view the commit history of a Git repository.
```sh
git log
```
!["Git Command"](https://github.com/mohankrishna02/Git-commands/blob/main/images/git%20log.png "Optional Title")


