# git push 
When you have a [remote](./RENOTE.md) set up you'll beed to begin to move [commits](./COMMIT.md) ti the remote.  
This can be done with the command 'git push' . 
You cab attach a name and branch name to your command to specify where you're pushing to 
 
 git push origin main 
  
  This command will push the **main** branch to the remote called **origin** 
  Thiis means any commits that are in your local will be **pushed** to the remote  
   
    
### Upstram Tracking 
Instead of including the name of the remote and the branch you're on every time, you can set local branches to track an upstram branch. 
This means you can tell the branch to push to its assigned upstream remote branch by using the command 'git push' 
 
 Before doing so, you'll need to use the '-u' or '--set-upstream' flag. This can be done on an 'git push'. 
  
  git push -u origin main 
   
   After this command is used, you can just use 'git push' and it will function the same wa 
    
## Resources 
 
-  [Git Push Documentation](https://git-scm.com/docs/git-push) 
 
 [Back to home](../README.md) 
 