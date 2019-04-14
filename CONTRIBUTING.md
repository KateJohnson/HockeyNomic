# CONTRIBUTING

### How to contribute

To contribute to the blog do not make changes directly in the master repository. Changes can be made to the master repository through pull requests from a fork or branch. When you want to submit new work that you developed, you must push all your changes to your fork or branch. Then, please send a `pull request`.

#### How to fork?
Go to the main repository [here](https://github.com/KateJohnson/Hockeynomic).

On the right top corner, click on the `Fork` button.

Go to your forked version of this repository.

Clone that repository and create an R studio project.

1) Copy the sash key found under the Green Clone or Download button.
2) Go to R studio -> New Project -> Git -> Repostiory URL.
*Complete instructions can be found [here](https://happygitwithr.com/existing-github-first.html)*

Once you've cloned the repository and have an Rstudio project, set up the original repository as the upstream master. Do this from the terminal using the following commands:

```
git remote add upstream https://github.com/KateJohnson/Hockeynomic.git

git fetch upstream
git merge upstream/master
```

Whenever you want to update your own forked repository from the master repository, use the last two commands together, they work like a `git pull` and save it to your local computer.

If you want to update your forked version, use `git push` to send the new changes from your local computer to your forked GitHub repository.

Use meaninful committ messages!

#### How to branch?
Here are instructions for how to create and delete branches https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository
 
 #### Attribution
 
 This document is based off an example from some [excellent UBC Master's of Data Science student](https://github.com/UBC-MDS/seating_pref) 
