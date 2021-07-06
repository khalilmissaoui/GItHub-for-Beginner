# GItHub-for-Beginner
GitHub guide for new people , got the main commands to push or pull a repo . <br>
#### 📢 All im trying to do is to help you avoid the pain of watching 10 min yt vedio to push ur project in 1 min .

 🚩 There is a solution called GitHub desktop that you can download and it gives you a nice GUI with a good UX .

 :heavy_exclamation_mark: _for the quick promised **1min GitHub push from local to remote repo** you can skip the command introduction part_ 
## Okay lets start : 

The main important commands after `git` are:

.

├──  **init**: the init command is used to intiate a repository called **.git** so you can start using git commands inside your local repository .

├──  **commit**: this command helps you saves your changes , usually followed by a parameters **-m ' '** and you should type a message that will displayed later

├──  **add**: the add command is used to add your local changes to your remote repository 

├──  **status**: this command is used to keep track the status of your files wether if they are changed-**but not commited yet (RED) / committed (GREEN)**- or not │   in general.

├──  **branch**: this command is used to create a path diversity  (Having multiple routes to reach a destination) , u just create another route to code   

├──  **checkout**: this command works with **branch command** it shows ur current branch and **if** u add a branch name after it you switch to that branch . 

├──  **push**: command is used to publish new local commits on ur remote directory  , usually followed by **-u** then your branch name

├──  **merge**: use this command to merge two branches in the remote repository .  

├──  **fetch** : the fetch command downloads changes from ur remote repository  **but** it doesn't changes your **local**  working files (safe mode ✔️)

├──  **pull**: **in contrast of fetch command ** this command is used to update your current branch (local files) with the latest changes from your remote  repository.

└──  **clone**: This command downloads an existing remote repository to your local computer usually using the url your find after clicking the code icon 

---

### 🎏 here is probably your favourite part hahaha : 
> :heavy_exclamation_mark: you should be having an existing repository in your github account and  ssh key linked wuth ur github account  

  ✍️  $ git init
  
  ✍️  $ git add .
  
  ✍️  $ git status 
  
     📗 _everything should looks greeen here_ 

  ✍️ $ git commit -m “your commit message”  
  
  ✍️ $ git remote add origin https://github.com/YOUR-REPOgit-NAME/my_project.git
  
> ✍️ $ git remote -v : to check the origin’s URL matches the remote repository
  
  ✍️ $ git push 
  
> ✔️ _this would push to ur default branch_

🎉 **bang u got ur files uploaded to ur remote repo 🎉 🥳**

---
 
### :heavy_exclamation_mark: if you want to create a branch and upload to it
 
  ✍️  $ git init
  
  ✍️  $ git add .
  
  ✍️  $ git status 
  
  ✍️  $ git commit -m “your commit message”
  
  ✍️  $ git remote add origin https://github.com/YOUR-REPOgit-NAME/my_project.git
  
  ✍️  $  git branch -M " ur branch name "
  
  ✍️  $ git push -u origin " ur branch name "
  
  ---
  
### :heavy_exclamation_mark: **If you want to use _pull_ to** : 

 ✍️  $ git init
 
 ✍️  $ git remote add origin https://github.com/YOUR-REPOgit-NAME/my_project.git

> ✍️ $ git remote -v : to check if u r pulling from the right remote repo

  ✍️  $ git pull -u origin " ur branch name "




## 📑 source : 
 
https://stackoverflow.com/questions/42820840/how-to-push-changes-to-branch
 
https://www.atlassian.com/git/tutorials/using-branches/git-merge
 
https://www.varonis.com/blog/how-to-merge-in-git/
 
https://www.git-tower.com/learn/git/commands/git-push/
 
https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull/

https://www.git-tower.com/learn/git/commands/git-pull/

https://medium.com/@pinglinh/how-to-use-git-pull-80ad77a8afc6
 
 
