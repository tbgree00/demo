# Git Cheat Sheet
## Getting started

### Configure Git
Configure a user

```git config --global user.name tggittest```

configure an email

```git config --global user.email tggittest@gmail.com```

Generate SSH Key

``` ssh-keygen -t rsa -C tggittest@gmail.com```

Upload the SSH Key in your github account


### Clone a Repo locally

Find a repo to clone, if it's not yours, fork it to your account

Clone the account locally (using SSH in this example)

```git clone git@github.com:tggittest/demo.git```

### Work with files

Add the folder into you text editor or somehow edit your files

Edit README.md

Save your changes in the editor

Add all files to the git index

```git add .```

Commit your changes

```git commit -m "Comment goes here"```

Push your changes to the online repo

```git push```
