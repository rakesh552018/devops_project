# This is my First Devops Project. I'm planning to crete sample CI/CD Pipeline with git,github,jenkins.

I've create sample project folder locally
Initialted git init
created program files in local machine

Aim1 : implement and practice Git commands to achieve Versioning files in a project.

Steps

# Adding file to track
git add  
# Commiting changes
git commit -m "commit name"
# Create a branch
git branch "branch name"
# checkout to branch i.e switching to other branches
git checkout branch name
# Create a brach and check out to it
git branch -M "branch name"  
# How to check which branch i'm currently IN
git branch
# How to add repository to Github

Maheshs-MacBook-Pro-2:msquare_javaproject_1 maheshchaganti$ git branch
  delete_branch
  master
  mjp1_prod
  mjp1_stage
* mjp1_test
Maheshs-MacBook-Pro-2:msquare_javaproject_1 maheshchaganti$ git add remote 
fatal: pathspec 'remote' did not match any files
Maheshs-MacBook-Pro-2:msquare_javaproject_1 maheshchaganti$ git remote add msquare_javaproject_1 git@github.com:rakesh552018/msquare_javaproject_1.git
Maheshs-MacBook-Pro-2:msquare_javaproject_1 maheshchaganti$ git remote -v
msquare_javaproject_1	git@github.com:rakesh552018/msquare_javaproject_1.git (fetch)
msquare_javaproject_1	git@github.com:rakesh552018/msquare_javaproject_1.git (push)
Maheshs-MacBook-Pro-2:msquare_javaproject_1 maheshchaganti$ git push msquare_javaproject_1
fatal: The current branch mjp1_test has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream msquare_javaproject_1 mjp1_test
# How to connect git to github and then push to repository
https://articles.assembla.com/en/articles/1136998-how-to-add-a-new-remote-to-your-git-repo

1. create repository in github
2. # set a new remote
   git remote add "reponame" "ssh or https github repo path"
3. # Verify new remote
   git remote -v
4. # push your changes into your remote repo execute the git push <remote> <branch> command:
   git push <your_remote_name> <branch name>

   test




