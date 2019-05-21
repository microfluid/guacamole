# HONGXING'S NOTES
 
# github workshop beginer level

## git clone the repository from remote github

```
git clone https://github.com/microfluid/guacamole.git

```
## configure global 

```
git config --global user.name "microfluid"

git config --glob user.email "hhxing@gmail.com"

git config --global core.editor 'nano -w' # configue defaut txt editor as nano instead of VIM

```
-  Use nano to edit the README.txt file

``` 
nano README.md

```
- print the edited README file in shell

```
cat README.md
```
- check the status of the current branch 

```
git status

```
- Add the changes to  staging 

```
git add README.md
```
- Check the status again using 'git status'
- Commit the changes with short comments

```
git commit -m "a short message to describe what changes you made"
```
- Check the status again
- Push to the master branch

```
git push

```
## Check the changes history

- check the log book for all changes

```
git log

```
- Check the differences of one particular commit ID with master

``` 
git diff <log ID> master

```
- Overwrite the Changes to previous versions

```
git checkout <log ID> <file name>

```
- check diff with a number of line ???


``` 
git diff HEAD~<number of lines> <file name>

```
## Creat new branches

```
git branch <name of the new branch>

```
## pull the changes from master version on github remotly

``` 
git pull

```
# make changes in collaborator's repository

- go to github 
- got "settings"
- add collaborator
- git clone the collaborator's repository into local computer's collaborator's fold
```
git clone <https://github.com/collaborator's name/collaborator's repository/ collaboratorsproject

```
## make changes on the same line of the file and git push the changes before the git push from collaborator

```
nano hummus.md

```
- make changes on the first line of hummus.md file
- then git add, git commit and git push the changes before the action of collaborator

```
git status
git add hummus.md
git status
git commit -m "make changes on the first line"
git push

```
- to overcome the conflicts while editing the same line of the same file, the collaborator need to git pull first
- after git pull, the collaborator can decide which changes he/she wants to make in nano text editor and then push it via git push





git init my-repo

git clone
git add
git commit
git status
git push


git checkout master  

initiate a new git repository from existing fold
** git init
initiate an empty git repository 
** git add . 
add all file to staging

# git pull
update the local fold with the online master version


