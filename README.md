# First Contribution :beginner: :rocket: :HackertoberFest: 2020
---
A project to help new developers to get started with GitHub with first Pull Request

It's difficult when you do something for the first time. Especially when you are collaborating, making mistakes isn't a comfortable thing. As open source is all about collaboration and working together.That is why this project was created to help new developers to make their first contribution and start their journey as a developer and contributing to the open source.

### I can watch online tutorials and learn why this?

Reading articles & watching tutorials can help, but what's better than actually doing the stuff in a practice environment? This project aims to provide beginners a simplified way to start contributing to open source.So If you are looking to make your first contribution to open source.This is the right place. Follow the following steps to get you started.

If you don't have git, [install ]( https://help.github.com/articles/set-up-git/) it from here.

## 1. Fork this Repository

Fork this repository by click on __fork__ button on the top right corner of this page.
This will create a copy of this repository in your account.

## 2.Clone Repository

* Now you are at your forked repository at your profile.
* At the right side corner find  *code* button
* Now clone this repo to your machine. Click on the code button and then click the *copy to clipboard* icon.
* Now go to location on your computer where you want to store the local copy of this repository, where you will work on it.
* After this, open a terminal and run the following git command:
--
`git clone url-you-copied`

For eg:
`git clone https://github.com/your-github-username/first-contributions.git`

where `your-github-username` is your GitHub username.

## 3.Create a branch

Change to the repository directory on your computer (if you are not already there):
`cd first-contributions`

Now create a branch using the `git checkout` command:
`git checkout -b <add-your-full-name>`

For example:
`git checkout -b add-salim-kumar`

## 4.Make necessary changes and commit

Now open `Contributors.md` file in a text editor. Refer to this [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) which gives information on how to use Markdown which is used to write in GitHub MD files

In this case, add the following line at the end of `Contributors.md:`

`- [Your-name](https://github.com/Your-username)`

Make sure there is no space between `](` . Save the file.

Go again to terminal and go to project directory and execute the command `git status`, you'll see there are changes which are unstage. Add those changes to the branch you just created using the `git add` command:

`git add Contributors.md`

Now commit those changes using the `git commit` command:

`git commit -m "Add <your-name> to Contributors list"`

For Example: 
`git commit -m "Add Salim Kumar to contributors list"`

__Caution:__ Don't forget to add `-m` it specifies message to commit. If you forget it will take you to vim terminal which is difficult to operate.

## 5.Push changes to GitHub

Push your changes using the `git push` command:
`git push origin <branch-name>`

replacing `<branch-name>` with the name of the branch you created earlier.

## 6.Submit your changes for review

Now go to your repository on GitHub, you'll see a  `New pull request` button.  Click on that button.
It will compare your branch with the original repository. Check if the comparing branch is your created branch

Now submit the pull request.

Soon I'll be merging all your changes into the master branch of this project.

---
Cheers :grin:

You created your first contribution to open source :clap:
****
If you like this please *__star__* this [repository](https://github.com/atulnair/first-contributions)

---
## What Next??

* You can work on other projects just search the organisation you like and see for **"Good First Issue"**.

__Note :__ Always read README.md file of the projects it contains the instructions for working up and setting up of the projects.


