# Git Basics For Beginner 

**1. How to clone a new repository into locally**
1. Go to a local directory using git bash 
2. git clone <clone-link> folder name
	the folder name is required
3. Add your fork to the main master branch - > git remote add upstream <link>
4. Check by using git remote -vv 
	
**2. How to push code to new git repository 1st time**
You have already created a new git repository on github
1. git clone empty repository 
2. git clone <fork_git_clone_link>
2. git remote add <master_clone_link>
4. git remote --v
5. Later go to local folder, 
6. git init -> to initiate the git in the local repository
7. git add . / git add files/folder name
8. git commit -m "Message"
9. git push -u origin master / git push -f 

**3.To create a new branch**
1. git checkout -b <Newbranchname>

**4 To list all the branch**
1. git branch 

**5. To switch to another branch**
1. git checkout <branchName>

**6. How to pull or fetch**
1. git pull 
2. git fetch

**How to amend the old commit**
1. Do the changes locally if required
2. git add. / git add <filename>
3. git commit --amend
4. Then it will open the vi editor window, later make save using "#wq!"
5. Then, push to branch Eg. git push -f 
