# per project user name and global user name 

git config user.name "Your project specific name"
git config user.email "your@project-specific-email.com"

global setting 
git config --global user.name "Your global username"
git config --global user.email "your@email.com"

verify the setting
git config --get user.name
git config --get user.email
git config --global --get user.name
git config --global --get user.email

# git  save the passwrod in local 

$ git config credential.helper store
$ git push http://example.com/repo.git
Username: <type your username>
Password: <type your password>
$ git help credentials
