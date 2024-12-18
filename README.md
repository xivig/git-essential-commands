# git-essential-command
**
Step by step git essential commands
**
# First step after creating repository
# …or create a new repository on the command line

echo "# wordpress-theme-portfolio" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin ``https://github.com/yisxa/wordpress-theme-portfolio.git``

git push -u origin master

# …or push an existing repository from the command line
git remote add origin ``https://github.com/yisxa/wordpress-theme-portfolio.git``

git push -u origin master

## Step 1
## creating project directory and switching in it

```
makdir new-project && cd new-project
```

## git initialize
	git init

## checking status for tracking the files and folders changed
	git status

## git global configuration setting

	git config --global user.name "Cyberabc"
	git config --global user.email "abc@rediffmail.com"
	git config --global color.ui true

## Step 2
## git remote adding file to local repository so that you can host(upload) file to Github without hiccup
	git remote add origin https://github.com/yisxa/abc.git
	git remote -v
	git status

## git add all files to staging area
	git add -A
	git commit -m 'readme.md file edited by Cyberabc'
	git push -u origin master

## git rename remote Repository
	git remote rename origin php-oop

## git clone a remote repository
    git clone https://github.com/yisxa/oop-php.git

## Step 3
## git add all files to staging area
	git status
	git add -A
	git commit -m 'readme.md file edited by Cyberabc'
	git push origin master

## git push origin master forcefully
	git push origin master -f

## git .gitignore file for node modules
	touch .gitignore && echo "node_modules/" >> .gitignore

## git add particular files
	git add .gitignore package.json package-lock.json README.md

## git remove a already added node modules
	git rm -r --cached node_modules && touch .gitignore && echo "node_modules/" >> .gitignore

## git push command
	git push --help
	git push --prune
	git push --set-upstream origin master
	git push --delete
	git pull origin master
	git stash
	git stash pop
	git config --global push.default current

## git fetch the remote file
	git pull

## git pull request for remote files
    git pull https://github.com/yisxa/responsive-webdesign-xivig.git

## git creating a branch
	git branch branch_name

## git switching branch
	git checkout branch_name

## git single step creating branch and checkout
	git checkout -b branch_name

## git merging branch with master
    git merge origin master
