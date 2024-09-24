
## GIT Commands
- `git init` - initialize git repository inside an opened directory. It is an hidden file that can be visible using ls -a command
Staging Area is intermediate place where files can be picked to commit

- `git status` - will show files that are in the working directory but not yet in Staging Area (aka Untracked files). Untracked files will show in red. To add files to staging area use git add command
- `git add` <file_name> - move file to Staging Area by file name
- `git add` . - move ALL untracked files to Staging Area
- `git commit` -m <"comment"> - command to commit to start tracking changes. -m is used to add a comment about changes that were made. Comments should be as details as possible and written in present tense.
- `git log` - command to see commits that had been made
- `git diff` <file_name> - command to see differences between current version and last save point in git repository
- `git checkout` <file_name - command to roll back file to the last checkpoint when it was committed

##GITHUB
Github is a remote repository to store Main Branch is a timemline of various commits. This is where main progress is saved or committed.

- `git remote add <name> <url>` - command to let Local Repository know that Remote Repository has been created

###
Quick setup — if you’ve done this kind of thing before or git@github.com:gennadytsoy/appbrewery-webdev.git Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

### …or create a new repository on the command line
```
echo "# appbrewery-webdev" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:gennadytsoy/appbrewery-webdev.git
git push -u origin main
```

### …or push an existing repository from the command line
```
git remote add origin git@github.com:gennadytsoy/appbrewery-webdev.git
git branch -M main
git push -u origin main
```
