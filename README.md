# Git-Basics
<hr>
first of select/create your working directory<br>
git init in your working directory <br>
create a file in your working directory <br>
for eg in this case git.py <br>
# >> git add git.py
this will add your file from working directory to your staging area
# >> git status
# >> git commit -m "staging area to local repo"

now create a repo in your github account <br>
here i have created Git-Basics <br>
now add remote github repo to your local storage <br>
# >>  git remote add origin "git@github.com:RaghavJindal13/Git-Basics"
# >> git pull origin master --allow-unrelated-histories
# >> ls
# >> git push origin master

<hr>
When cloning a GitHub repo, you sometimes come across an error saying:<br>

Permission denied (publickey).<br>
fatal: Could not read from remote repository.<br>
Please make sure you have the correct access rights<br>
and the repository exists.<br><br>

This calls for the creation of an SSH key.<br><br>
 
so now we will create our first SSH key<br>
# >> ssh-keygen
# >> cat ~/.ssh/id_rsa.pub
Now heading to the final part where I'll add the SSH key to my GitHub account. <br>
In your GitHub Profile open Settings. <br>
Go to the section for SSH and GPG Keys. Click the New SSH key button, write a suitable Title,<br>
 paste the copied Key and hit the Add SSH key button.<br>
<br>
