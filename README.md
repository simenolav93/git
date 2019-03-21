# HOW TO USE git & github

This is shortend version of: https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
and some extra


# Step 0: Install git and create a GitHub account 
# Step 1: Create a local git repository 
  - create a new project folder
  - run: `git init` in the project folder
# Step 2: Staging enviroment
  - `git status` showes what files you have made changes to or misses after the lates commit
# Step 3: Add a file to the staging environment
  - `git add .` or `git add fileName` adds the files to the commit(does not commit them)
# Step 4: Create a commit
  - `git commit -m "Your comment to this spesific commit"` Commits whatever is in the staging enviroment. 
  - `git log` shows all the commits made on the current branch of the local project(I think)
# Step 5: Create a new branch
  - `git checkout -b branchName` Creates a new branch and redirect you inn to the new branch
  - `git branch` Showes all the local branches. The branch with the asterisk is the current branch
  - `git checkout branchName` changes the current working branch to the chosen branchName
# Step 6: Create a new repository on GitHub
  - create your repository on github 
      and then open the connecton with the new repository and push the new project in it:
  - `git remote add origin https://github.com/yourGithubUserName/yourGithubRepositoryName.git`
  - `git push -u origin master`
# Step 7: Push a branch to GitHub
  - `git push origin branchName`
# Step 8: Create a Pull Request (PR)
  - everybody can make a pull to a project but only the project owner can accept if the pull is going to happend(actualy make the change to the master). This is almoste like asking for permission to make a change to the master branch.
# Step 9: Merge a PR
  - this have to be done in github. 
  - if you accept the pull request you are going to merge the master with the branch in the pull (might also be someone elses master branch of your project)
# Step 10: Get changes on GitHub back to your computer
  - if the master branch have been changed on github it have to be pulled before worked on. Or else it is going to be diffrent from the master on github
  - `git pull origin master`

