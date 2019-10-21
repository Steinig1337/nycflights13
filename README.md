# Week 5 Exercise: Analysis of flights data

This is the exercise belonging to week 5 of the course **Tools and Programming for Data Scientists** at the **University of Applied Sciences in Kiel**. This exercise is about working with Git, Github, and the R tidyverse. You should practice these topics as much as you can.

The context of this exercise is an analysis of flights departing from one of the three large New York City airports. During the analysis you will use 5 different datasets named `flights`, `airports`, `airlines`, `planes` and `weather`. *First*, you will analyse them separately and build up an understanding of the data. *Second*, you will join the datasets in order to answer more advanced questions.

## 1. Fork GitHub repository
Open https://github.com/tillschwoerer/nycflights13 and press the `fork` icon in the upper right side of the project page. Now the forked project should appear on your GitHub page in the list of your repositories. 

## 2. Clone and start RStudio project
- Copy the repository HTTPS url: Browse to https://github.com/<your_username>/nycflights13. Press `Clone or download` and copy the url. 
- Create a new RStudio project with Git version control: In RStudio Select `File` > `New Project` > `Version Control` > `Git`, then paste the url, select the directory on your computer where you want to store your project and click on `Create`. RStudio now clones the content of the GitHub repository to your local project directory. The content of the GitHub repository now appears in the Files pane of RStudio.

## 3. Create new branch  
To separate the official version (master) from development/experimentation, create a new branch. In the RStudio IDE you create a new branch by clicking the purple branching symbol in the Git tab. Chose a short, meaningful branch name (without any blanks) such as `EDA` or `development`. Leave `Sync branch with remote` activated and press `Create`. Now you switched into the new branch. (But you can always switch back to the Master in the upper right of RStudio's Git tab.) 

## 4. Tidy and analyze the  data
> This exercise is as much about R and the tidyverse as about Git and Github. 

So go through the `nycflight.Rmd` file and try to solve all the tasks described there, and additionally analyse all the questions that _you_ are interested in. 

After each of the sections, `commit` your changes to your development branch. For a commit you first have to `stage` the files that you want include in the commit (this choice is easy here, because there is just this Rmd file). Then you can inspect the `diff` to the last commit. Provide a meaningful commit message (such as "Add airlines section"), and press commmit. 

## 5. Push to GitHub
Whenever you like you can `push` your changes to the `remote` GitHub repository. Verify that your changes appear in the development branch of your GitHub repository, but not in its master branch.

## 6. Make pull request
In real life its likely that you want to merge your changes back into the original repository (the one you forked in the very beginning). You open a pull request on GitHub, some colleagues review your changes, and hopefully in the end they pull them into the original repository. 

We deviate from this realistic scenario here, because you are all working on the same tasks. Thus, once the results of 1 student are pulled into the upstream repository, every further pull request would just create a lot of merge conflicts.

Instead, open a pull request from your own master branch, "review" your changes in the development branch, and merge them into the master. Alternatively, you could make a pull request to the repository of one of your fellow students.

[How to do a pull request is described here](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork). 
