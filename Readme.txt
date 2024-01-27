
# Making Github locally modifier any changes can we done through local machine even repo create
<br/>
# Need to install Github CLI

## gh auth login > github.com

# Authenticate with coping the code generated and paste the code on the device portal open/sometime need to open manually
<br/>
# Github CIL comments
# Create Remote repository
## gd repo create "Repository-Name" "--Piblic/Private"
## can check it out the new repo is created sucess fulls by gh repo list
## Remote Repo can we deleted using gh repo delete Repo-name --yes
## can check it out the new repo is created sucess fulls by gh repo list

# Secong Git bash Commands
## Basic commands should be knows mkdir(Create new directory), rm(remove any file), cd(Current directory), ls(List all file in current directory) same as dir

## Need to copy the remote directory to local machines with git clone "latest repo url that wll be https://github.com//User-name/Repo-Name"
## Add new things file/Folder here "." is use as ALL or we can aslo use "-A" using git add .
## IF wanted to ready this for commit it to remote as well us git commit -m "Message to know when was this commited with updating what things"
## Add to ree reflection in remote use finally git push
## if at any instance if u want to stop add or commit can use git reset
## as if u want to get back to the previous version tht u last pushed can use git reset --hard HEAD~1


#Add set origin with specific repo
## 
<br/>
## git init // To create local repository
## git confi --global user.name "User_name"  #Add global user name from the github account
## git confi --global user.emial "Email_Addres"  #Add global use Email from the github account

# If using multiple Branch
## check current branch git branch
## Add new branch git branch Main
## Replace working of branch git checkout OtherBranchName
## Mirge two branch git merge anotherBranchWithCurrentBranch

## git init // To create local repository
# Add repo to origin
## if you do add it using git remote add origin need to pull this in the local 
## git remote add origin https://github.com/Github-User-Name/Repository-Name.git