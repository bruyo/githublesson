# Github lesson
Utiva git and github class.
## Introduction on how to git push from local desktop to github
Downloaded Gitbash (https://git-scm.com/downloads)
## Configure gitbash
git config --global user.name "name"  
git config --global user.email "email"
## Work with the configured environment
mkdir website  
cd website  
git init  
touch index.html
## Clone your github repository
git remote add origin url (this should be the url from your created repository and use http)
## How to push to Github
git add index.html  
git commit -m "Create index.html"  
git push origin master
