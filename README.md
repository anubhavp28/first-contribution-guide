![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103) ![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## Hello Learners!

Hello learners, learning how to use git and github, and making your first contribution can be a daunting task (We all have been there :smile:). We have created this repository to help you get started. You can learn and start contributing using this awesome guide for first timers. Just follow the steps given below.

# Steps:

## 1. Installing Git:

- Ubuntu:  `sudo apt-get install git`
- Windows: [Download](https://git-scm.com/download/win)
- Mac: [Download](https://git-scm.com/download/mac)

## 2. Making your first contributions

It's hard. It's always hard the first time you do something. Especially when you are collaborating, making mistakes isn't a comfortable thing. We wanted to simplify the way new open-source contributors learn & contribute for the first time.

Reading articles & watching tutorials can help, but what's better than actually doing the stuff in a practice environment? This project aims at providing guidance & simplifying the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.





<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

##Star this repository
Star this repository by clicking on the fork button on the top right corner of this page. 
You can star repositories to keep track of projects you find interesting and discover similar projects in your news feed.

## Fork this repository

Fork this repo by clicking on the fork button on the top right corner of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repo to your machine. Go to your GitHub account, open the forked repo, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/first-contribution-guide/
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository in GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contribution-guide
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-anubhav-patel
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)



## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/create-pull-request.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats!  You just completed the standard *fork -> clone -> edit -> pull request* workflow that you'll encounter often as a contributor!



You could join our zulip organisation, in case you need any help or have any questions. [IIITKalyaniFOSC on Zulip](https://iiitkalyanifosc.zulipchat.com/).
