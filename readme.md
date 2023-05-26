# one hastag for main header  !
.md extension means markdown ti is an easy way to edit the text
## subheading
 there is one hidden folder .git that saves all the files that saves your commit
 ## 
 check git status to know the file status whether file is added new or modified
 if file is untracked by git use git add . ,. means all files or you can mention each file name 
 after git commit -m , m is message which shows why you want to do commit
 ## SSH keys 
 git push is used to push the files in github in remote repository 
 then to show github that you are owner of your account then use ssh-keygen -t rsa -b 4096 -C"email
 then to find key use ls | grep testkey
 ## to create the key 
 use ssh-keygen
then select name 
and password and then copy the path where key is present then use cat path and use ls to ls all the files and the copy the ssh key and add in github account to clone your repository !!
testkey.pub means it is a public key 
testkey is private key which helps when we want to connect with github we show our private key to github that we created the public key 
## to copy something in terminal use pbcopy< ./ssh/testkey.pub
after adding key to ssh keys we want local git cli to know about the key we generated
option  is arguement of git push which means location of a git repository and master is the branch that we want to push to  