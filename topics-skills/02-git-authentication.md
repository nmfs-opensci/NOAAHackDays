---
title: GitHub Authentication
---

::: {.callout-note icon=false}

## Learning Objectives

-   tell git who you are
-   set up authentication so you can push up changes
-   clone a repository from the terminal
:::

## Tell Git who you are

First open a terminal and run these lines. Replace `<your email>` with your email and remove the angle brackets.

```
git config --global user.email "<your email>"
git config --global user.name "<your name>"
git config --global pull.rebase false
```


## Authentication

You need to authenticate to GitHub so you can **push** your local changes up to GitHub. There are a few ways to do this. For the JupyterHub, we will mainly use `gh-scroped-creds` which is a secure app that temporarily stores your GitHub credentials on a JupyterHub. But we will also show you a way to store your credentials in a file that works on any computer, including a virtual computer like the JupyterHub.

## Preferred: `gh-scoped-creds`

If you get the error that it cannot find `gh-scoped-creds`, then type 
```
pip install gh-scoped-creds
```
in a termnal.


1. Open a terminal
2. Type `gh-scoped-creds`
3. Follow the instructions
4. FIRST TIME: Make sure to follow the second pop-up instructions and tell it what repos it is allowed to interact with. You have to go through a number of pop up windows.

Jump down to the "Test" section to test.

## Also works: Set up authentication with a Personal Token

This will store your credentials in a file on the hub. This is not as secure since the file is unencrypted but sometimes `gh-scoped-creds` will not be an option.

### Step 1: Generate a Personal Access Token

We are going to generate a **classic** token.

1. Go to https://github.com/settings/tokens
2. Click Generate new token > Generate new token (classic)
3. When the pop-up shows up, fill in a description, click the "repo" checkbox, and then scroll to bottom to click "Generate".
4. SAVE the token. You need it for the next step.

### Step 2: Tell Git who your are

1. Open a terminal in JupyterLab or RStudio
2. Paste these 3 lines of code into the terminal
```
git config --global credential.helper store
```

## Test

1. Go to https://github.com/new
2. Create a PRIVATE repo called "test"
3. **Make sure to check the "Add a README file" box!**
4. Open a terminal and type these lines. Make sure to replace `<username>`
```
git clone https://github.com/<username>/test
```
5. If you properly authenticated, git will ask for your username and password. At the password, paste in the TOKEN not your actual password.


