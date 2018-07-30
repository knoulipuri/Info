# Github console commands
1. git clone <url form github>
2. cd <ur project folder>
3)It will be in master branch, then give "git checkout <specifiedbranchname>" and hit enter, it swithes to specified branch.
4)git checkout -b <localbranchname>->switches to newly created local branch
5)Make any changes in files in your local branch
6)git status->will display the files you've changed and those you still need to add or commit
7)git diff->View all the merge conflicts
  (or)
 git diff --base <filename> ->View the conflicts against the base file
  (or)
 diff <sourcebranch> <targetbranch> ->Preview the changes, before merging
8)git add <filename>->After you have manually resolved any conflicts, you mark the changed file
   (or)
 git add .(its dot) ->to add these changed files to the activity
9)git commit -m "Commit message"
  ->will show us the changed file count, this means the changed files arw checked-in.
  if uesr wants to deliver or move these changed files from local branch to specified branch then user should swith to specified           branch first then merge with local branch changes.
  Commit changes to head (but not yet to the remote repository)
10)git checkout <specifiedbranchname> ->means to move to specified branch
11)git merge <localbranchname> ->to merge the specified branch with local branch changes.
  To merge a different branch into your active branch
12)git push ->to push the changes to specified branch and after push only, we can see those changes in GITHub specified branch repository.
 
Note:
take fresh code from  git or, pull the code from git before pushing your changes.
