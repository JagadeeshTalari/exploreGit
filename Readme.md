# Practicing and Learning Git 

### To find where git installed: 
- where git for windows &
- which git for Mac

### To find which version of git is installed on your system:
- git --version

### To give UserName & email :
- git config --global user.name "Jagadeesh"
- git config --global user.email "talarijagadeesh55@gmail.com"


### To get help related to commands :
 - git help config
 - git help < verb >

### Some of the Important Terms that you should learn in Git : 

1. Commit
2. Clone
3. Tracked/Untracked files
4. Branch
5. Staging

### Learning How to Clone a repo and push code into github from remote location (with different device).

- We should use " git clone < url of repository >" to clone/fork a repo.
- After that we can push the code to git hub.


### If we made changes in the code and messed it and now we want to get the file back to it's original state (which is in the github repo) i.e, simply undo the changes you have made to the code and bring it back to it's previous commited or pushed state then we should use...

- git checkout -- < filename >

### If you added the commit and you only made very few changes and don't want two seperate commit's and you want to include previous changes and the latest changes under one commit  (or)

### / if your didn't like your commit message or want to change your last commit message. Note: This can be done only for last commit only. Then ammend can be used.


- git commit --ammend -m "Learned how to use ammend and added code"


### if we want get the file version of previous commit's then we should use checkout < commit SHA > -- < fileName >

- git checkout  bd1d55f -- myfunction.txt
- git diff --staged
- git reset HEAD myfunction.txt


-git rm --cached my.php

-newfolder with no files in it then git will not keep track of that 
solution for it is :
- .gitkeep (invisible)
- simple.txt (visible)



- git ls-tree < HEAD/master/ SHA no. / HEAD~2 / etc >

To see the what are the files included at that stage