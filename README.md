# git_demo_again


-step1: Created a repo on github account
-step2: Created a same name  folder in local in your pc.
-step3: Create any file in that folder for versioning.
   eg: 'echo "# git-demo-again" >> README.md
-step4: initialize git in your local folder 
   eg: 'git init'
-step5: to check the status (untracked -'Red' /track file - 'Green') of your github repo
   eg: 'git status'
-step6: to  move file from untrack files to track files
   - eg:'git add', or 'gid add -A' (add all file into tracking)
   - eg:'git add <file-name>' (add only specific file to tracking)
   - eg:'git add *.csv' (add only specific files)
   - let suppose you want to move file from tracking to untracking again (tick wapis 
   krdou)
      - git 'rim --cached <file>'
-step7: to make file ready to to push we do commit (send to airport)
     -eg: 'git commit -m' "any meaningful comment"   
-step8:to rename the branch from 'master' to 'main'
     - eg: 'git branch -M main'
-step9:to set the origin for your local repo for github repo (travelling to destination 
setting)  
     - eg: git remote add origin 'https://git@github.com:MuhammadYousuf8124/get-demo-again.git'

## Second time 

- 'git add.'
- 'git commit -m "any message:"
- git push



## Branching 
-step01: to check on which branch you are 
   -eg:'git branch'
-step02: to move and create new branch
   -eg: 'git checkout -b task/development-branch'
   - if branch already exist eg: 'git checkout <branch_name>'