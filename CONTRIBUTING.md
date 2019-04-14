# CONTRIBUTING

### How to contribute posts

[KateJohnson](https://github.com/KateJohnson) is the website maintainer and will work directly on the master branch. To contribute posts, do not make changes to this repository directly. Changes can be made on your local version of the repository, and then added to the master repository through pull requests from a fork or branch. When you want to submit new work that you developed, you must push all your changes to your fork or branch. Then, please send a `pull request` to merge with the master branch (which will automatically update the website).

#### How to fork?
Go to the main repository [here](https://github.com/KateJohnson/Hockeynomic).

On the right top corner, click on the `Fork` button.

Go to your forked version of this repository.

Clone that repository and create an R studio project using the following steps.

1) Copy the sash key found under the Green Clone or Download button.
2) Go to R studio -> New Project -> Git -> Paste Repostiory URL.
*Complete instructions for linking Git to RStudio can be found [here](https://happygitwithr.com/existing-github-first.html)*

Once you've cloned the repository and have an Rstudio project, set up the original repository as the upstream master. Do this from the terminal using the following commands:

```
git remote add upstream https://github.com/KateJohnson/Hockeynomic.git

git fetch upstream
git merge upstream/master
```

Whenever you want to update your own forked repository from the master repository, use the last two commands together, they work like a `git pull` and save it to your local computer.

If you want to update your forked version, use `git push` to send the new changes from your local computer to your forked GitHub repository.

Use meaningful committ messages to help us understand pull requests!

#### How to branch?
Here are instructions for how to create and delete branches https://help.github.com/en/articles/creating-and-deleting-branches-within-your-repository
 
### Issues

Use issues to suggests changes to the website or additional features you'd like added

### Sample workflow

1) Create a local version of the forked repository as described above.
2) Conduct analysis and visualizations in a seperate R Studio Project. Write the blog post as an .rmd or .md document.
3) Add the blog post to your local version of Hockeynomics under content -> [post](https://github.com/KateJohnson/Hockeynomic/tree/master/content/post). Add the images that are linked to in your post to [static](https://github.com/KateJohnson/Hockeynomic/tree/master/static) in a folder with the same name as the file with your blog post.
4) Submit a pull request to merge your local changes with the master.
 
#### Attribution
 
 This document is based off of a group project from some excellent [UBC Master's of Data Science students](https://github.com/UBC-MDS/seating_pref) 
