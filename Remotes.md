# git remote 
When working with git,a **remote** is any git repository that is not on the machine you're working on. The counterpart to this **local**, or the machine that is being developed on. 
Take GitHub for example. while git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others. 
 
**Note**: While the repositories (Local and Remote) are related and track the same project, they can have different states if changes are not shared between the two 
 
  
  ### Addubg a remote 
  A remote can be added with the 'git remote add' command, followed by the name and location of the remote. 
  the name is a local name, meaning it's your label and does not impact the actual remote whatsoever. 
   
   git remote add origion https://github.com/ElevenfiftyAcademy/GitFundamentals.git 
    
       
### Removing a remote 
 
 A remote can be removed with the 'git remote remove' co,,amd, followed by the name of the remote. 
  
  git remote remove origin 
   
    
## Resources 
 
 - [Git remote Documentation](https://git-scm.com/docs/git-remote)  
  
  [Back to Home](../README.md) 
  