Install and configure git
```
sudo apt-get install git
git --version
git config --global user.name <username>
git config --global user.email <email>
git config list
```
change email address and user name for a specific project
```
git config user.name <username> && git config user.name
git config user.email <email>  && git config user.email

```
upload the project to a new git repository
* create a new repo in github **without readme file**
* Initialize the git
* Commit all the files
* change the repo name from master to main
* add the remote origin
* push the repo
```
git init
git commit -m "first commit"
git branch -M main
git remote add origin <repo https url>
git push -u origin main
```
