# Git with Teams

To work on a team project, we need to take advantage of some Git functionality that we haven't needed to use previously on our pair projects: branching and merging.

Below is a broad overview of how your changes can be added to the shared repository for your team project.

![](https://i.stack.imgur.com/WpYGV.png)

The workflow for working in a team follows these steps.

1. Build a repo and make all team members collaborators.
2. Clone master to each pair's desktop creating a local master branch.
3. Create a feature branch locally to work on a new feature.
4. Complete work on feature branch.
5. Pull any changes from remote master to local master. If there are changes, merge master into the feature branch and resolve any conflicts.
6. Push updated, completed branch \(all tests pass, functionality in place\) to remote master.
7. Navigate to branch and create a pull request.
8. Collaborators review new branch code.
9. Merge.
10. Delete feature branch.

### Git Commands Reference

* **git checkout -b branch-name**: creates and checks out a new branch named branch-name
* **git branch**: lists current branches with an asterisk by the current branch
* **git branch** -D branch-name: delete the branch named branch-name
* **git merge branch-name**: merge branch-name into the current branch
  -** git clone remote-name**: creates a local repository from a remote repository
* **git remote**: lists currently associated remote repositories
* **git remote add remote-name url**: adds a new remote repository with the name remote-name using the URL of the remote repo on github
* **git push remote-name branch-name**: pushes your branch \(branch-name\) to a remote repository \(remote-name\)
* **git pull remote-name branch-name**: pull the latest changes from a remote repository to your repository \(e.g. git pull origin master\)

# Summary

git checkout `-b _branch-name_`: creates and checks out a new branch named branch-name git branch: lists current branches with an asterisk to indicate the one you're currently on git branch -D`_branch-name_`: delete the branch named branch-name git merge`_branch-name_`: merge branch-name into the current branch git clone `_remote-name_`: creates a local repository from a remote repository git remote: lists currently associated remote repositories git remote add `_remote-name_ _url_`: adds a new remote repository with the name remote-name using the URL of the remote repo on github git push remote-name `_branch-name_`: pushes your branch \(branch-name\) to a remote repository \(remote-name\) git pull remote-name `_branch-name_`: pull the latest changes from a remote repository to your repository \(e.g. git pull origin master\)

