# nycflights13
Analysis of flights and weather data




**1. Fork GitHub repository:** Open https://github.com/tillschwoerer/nycflights13 and press the `fork` icon in the upper right side of the project page. Now the forked project should appear on your GitHub page in the list of your repositories. 

**2. Clone to your computer and start a new RStudio project:** 
- Copy the repository HTTPS url: Browse to https://github.com/<your_username>/nycflights13. Press `Clone or download` and copy the url. 
- Create a new RStudio project with Git version control: In RStudio Select `File` > `New Project` > `Version Control` > `Git`, then paste the url, select the directory on your computer where you want to store your project and click on `Create`. RStudio now clones the content of the GitHub repository to your local project directory. The content of the GitHub repository now appears in the Files pane of RStudio.

**3. Create a new branch:**  
To separate the official version (master) from development/experimentation, create a new branch. In the RStudio IDE you create a new branch by clicking the purple branching symbol in the Git tab. Chose a short, meaningful branch name (without any blanks) such as `EDA` or `development`. Leave `Sync branch with remote` activated and press `Create`. Now you switched into the new branch. (But you can always switch back to the Master in the upper right of RStudio's Git tab.) 

**4. Tidy and analyze the New York City Flights data**
> This exercise is as much about R and the tidyverse as about Git and Github. 

So go through the `nycflight.Rmd` file and try to solve all the tasks described there, and additionally analyse all the questions that _you_ are interested in. 

After each of the 6 sections, `commit` your changes to your development branch. For a commit you first have to `stage` the files that you want include in the commit (this choice is easy here, because there is just this Rmd file). Then you can inspect the `diff` to the last commit. Provide a meaningful commit message (such as "Add airlines section"), and press commmit. 

**4. Push to GitHub:** Whenever you like you can `push` your changes to the `remote` GitHub repository. Verify that your changes appear in the development branch of your GitHub repository, but not in its master branch.

**5. Make a pull request:** You would like to merge your analysis and results back into the original repository. So, open a pull request to the GitHub user from which you have forked the repository. To do so, follow the steps described [here](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork). 
