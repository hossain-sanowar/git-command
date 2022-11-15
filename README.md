# git-command
this is CLI command
# git documents

https://git-scm.com/
# github-cli-test

1. …or create a new repository on the command line
```
echo "# git_cli_test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:hossain-sanowar/git_cli_test.git
git push -u origin main
```
2. …or push an existing repository from the command line

```
git remote add origin git@github.com:hossain-sanowar/git_cli_test.git
git branch -M main
git push -u origin main
```

## push branch to main
```
git branch --move master main
git push --set-upstream origin main
```
## remove branch 
```
git push origin --delete master
```
# git status
```
git init
git log
git branch
git brach -D <file_name> #delete branch file
git pull <repository>
git push origin main
git commit -m "salary prediction"
git add .
git push --force origin main
git push -u origin main
```
## get commit 1 command ahead, then what should we do?
```
git pull origin main
```
## current change and incoming change
`remove conflict message, then push again`
