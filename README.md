Git Command
 1. Fisrt open the Git Bash Editor.
 2. Go to the project folder. Example : If the project name is MyMicroService.
    Then Goto before that /e/STS_WORKSPACE/MyMicroService
	cd /e/STS_WORKSPACE
 3. Then type git init -- Initializes the local repository, Each project has its own repository.
    Please make sure you run this command just before your project folder.
	ex: inside cd /e/STS_WORKSPACE
 
 4. git remote add origin https://github.com/ArindamCts007/Test-Springboot.git  
    This command allign the remote repository with your local repository.
	
 5. To see your remote repository
    git remote -v
	
  6. git add . . 
     This command add your code from local machine to local repository.
	 
  7. git commit -m "My First Commit"  , The comment before check in
  8. git push -u origin master   , Actually push the local code to the remote repository.
  
  9. git push origin :master
