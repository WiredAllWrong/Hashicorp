# Important Git commands to understand 

To assist you in understanding Git concepts and related commands, Git command definitions are provided below.

**`git push`** - Pushes changes from your local branch to a remote repository.

**`git fetch`** - Fetches changes from a remote repository into the tracking branch.

**`git pull`** - Pulls changes from a remote branch into the tracking branch and merges the changes into your local branch. 

**`git merge`** - Integrates and merges changes from another branch.  


## `Git push`

`git push` takes your current branch and checks the tracking branch and the remote repository it is connected to. 
Once the tracking branch and remote respository are determined, changes are pulled from your local branch and pushed to the remote repository. This is how code is synchronized and shared with a remote repository. 
 

## `Git pull`, fetch and merge commands
If the remote repository diverges from your local branch, commits in the remote repository must be pulled and pushed to your local branch using `git pull` and `git merge` commands.

The `git fetch` command reads your current branch to check for a tracking branch and pulls the changes from the remote repository into the tracking branch. Next step is to merge the changes with your local branch. The `git merge` command integrates the independent lines of development into a single branch. We recommend you use `git fetch` followed by `git merge` to ensure you understand the changes merging into your local branch before the merge actually happens. 

To merge the changes into your local branch, run the following commands:

 1. `git fetch`
 1. `git merge origin/master`   
  
The git merge command is incredibly useful in ensuring that development stays organized, as it allows you to easily move between the various branches and ensure all changes are accounted for and up-to-date.

