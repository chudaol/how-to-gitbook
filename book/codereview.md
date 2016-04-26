# Code review before submitting changes

Sometimes you want your colleagues to review your changes before submitting them to the master branch (the branch which by default gitbook consumes your changes).

In this case you should create a separate branch, make your changes, push the branch and create a pull request on github.

* create a branch
* edit your book
* commit and push changes
* create pull request
* wait for it to being merged

### Create a branch

Just run a command

    git checkout -b <branch name>
    
![](../img/create-branch.png)

### Edit your book

Write your text, check your changes locally in your browser

![](../img/check-changes.png)

### Commit and push your changes

Run

    git add .
    git commit -am "Added a new change related to the new chapter"
    git push origin <branch name>
    
![](../img/push-new-branch.png)

### Create pull request

Go to your github page and click on Compare & pull request button:

![](../img/click-compare-and-pr.png)




