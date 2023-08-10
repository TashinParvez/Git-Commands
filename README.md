# Git-Commands
 

## How do I properly force a Git push? [**Force push**]  
 
 `git push origin [your_branch_name] --force`
   
   Example: git push origin main --force

   


## Changes not staged for commit problem [**Staged Changes**]

committing these changes requires two phases
 - first phase is adding those changes to the **staging area** [ In the staging area these changes would be called staged changes ]
- second phase is taking a snapshot of the staging area
then you can commit and push

so how do I add changes to the staging area?

`git add [file-name]`

OR

Add all new and changed files to the staging area
   
`git add -A	`

To take snapshot

`git commit -m "[commit message]"`

Now you can push




## How to add all untracked files

 


