# How to Contribute

Since this is a beginner friendly project, here are some instructions on how to help contribute to this project.

## Getting started

* In a terminal, go to the folder you want to clone this repo in (I like to keep a GitHub folder in my documents)
* run `git clone https://github.com/JemLuu/lecture-rot.git`
  * Note you might have to set up a personal access token (PAT)
 
## Making changes

* Once you have the repository cloned, you now have all the code
* You are likely on the `main` branch
* To make changes, you want to create your own branch. Having your own branch will store store all your changes separately to the `main` branch.
* To do so:
  * run `git checkout -b 'name/feature'` (the `-b` indicates making a new branch)
  * ex: `git checkout -b 'jeremy/listener'`
* run `git branch` to see which branch you are on
* Try making some changes on `your branch` and then run `git checkout main`. Did you notice that your changes dissapeared? run `git checkout your-branch` to go back.

## Committing your changes

* When you make changes, you can run these commands in a terminal from the *root* of the repository.
* **Make sure you're in your branch**
  * `git add .`
  * `git commit -m 'your commit message'`
  * `git push`
* Now your changes are pushed up to github!

## Making a PR

* Go to `https://github.com/JemLuu/lecture-rot`
* At the top it should say `your-branch has had recent changes, do you want to create a pull request?`
* Click the big green button to create a pull request
* Scroll down and click the green button for `open pull request`
  * *Note there is a git command to create a pull request, I just think its easier to do so on the web*

## After you've made your pull request

* You should request someone as a reviewer
* You might have merge conflicts if people have been changing the code as well
  * We'll deal with these as they come
* To merge your PR, click the green squash and merge button!
