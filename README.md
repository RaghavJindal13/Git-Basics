# Git-Basics
<br>
first of select/create your working directory
git init in your working directory
create a file in your working directory
for eg in this case git.py 
# >> git add git.py
this will add your file from working directory to your staging area
# >> git status
# >> git commit -m "staging area to local repo"

now create a repo in your github account 
here i have created Git-Basics
now add remote github repo to your local storage
# >>  git remote add origin "git@github.com:RaghavJindal13/Git-Basics"
# >> git pull origin master --allow-unrelated-histories
# >> ls
# >> git push origin master

<br>
When cloning a GitHub repo, you sometimes come across an error saying:

Permission denied (publickey).
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.

This calls for the creation of an SSH key.
 
so now we will create our first SSH key
# >> ssh-keygen
# >> cat ~/.ssh/id_rsa.pub
Now heading to the final part where I'll add the SSH key to my GitHub account. 
In your GitHub Profile open Settings. 
Go to the section for SSH and GPG Keys. Click the New SSH key button, write a suitable Title,
 paste the copied Key and hit the Add SSH key button.
<br>
