# To Install the Git Bash
 Install the [GitBash](https://git-scm.com/downloads) for your PC.


# To upload the files in the Local Machine to the Github repository
## Steps
1. Open the Git Bash in your Project Folder.
2. Type 
`git init`
3. Now, create a remote using 
   `git remote add origin <repolink>`
4. Now check the access using
   `git remote -v`
5. Now add the files to the local remote using
   `git add .`
   > . will add all the files in your folder to the local remote.

   To add a specific file to the local use
   `git add <FileName>`

6. Now commit the changes using 
   `git commit -m "COMMENT"`
7. Now push the changes to the Github Repo using 
   `git push origin <branchname>`
   > Here it is master
   
   Your files will be pushed to the Github Repository.   
