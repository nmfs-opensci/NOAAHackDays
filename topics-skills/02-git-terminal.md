---
title: Basic Git/GitHub Skills in the Terminal
---

::: {.callout-note icon=false}

## Learning Objectives

- Learn how to use Git from the terminal
- Practice 4 basic Git/GitHub skills: cloning, committing, push/pull

## Prerequisites

- Read [Intro to Git](topics-skills/02-git.html)
- Have a [GitHub](https://github.com/) account
- [Git Authentication](topics-skills/02-git-authentication.html)

:::

## Create a GitHub account

For access to the NMFS Openscapes JupyterHub, you will need at GitHub account. See the main HackHour
page on how to request access (NOAA staff). For NMFS staff, you can look at the [NMFS OpenSci GitHub Guide](http://nmfs-opensci.github.io/GitHub-Guide/#create-a-github-user-account)
information for how to create your user account and you will find lots of information on the
[NMFS GitHub Governance Team Training Page](https://sites.google.com/noaa.gov/nmfs-st-github-governance-team/training) (visible only to NOAA staff).

## Setting up Git Authentication

Before we can work with Git in the JupyterHub, your need to do some set up. Do the steps here: [Git Authentication](topics-skills/02-git-authentication.html)

## Git in the terminal

You will need to open a terminal in JupyterLab or RStudio.

## The Key Skills

* Skill 1: Create a blank repo on GitHub
* Skill 2: Clone your **GitHub** repo
* Skill 3: Make some changes and commit those local changes
* Skill 4: Push the changes to GitHub

* Skill 1b: Copy someone else's GitHub repository

## Let's see it done!

### Skill 1: Create a blank repo on GitHub

This skill is done on GitHub.com.

1. Click the + in the upper left from YOUR GitHub page.
2. Give your repo the name `Test` and make sure it is public.
3. Click new and check checkbox to add the Readme file and `.gitignore`
4. Copy the URL of your new repo. It's in the browser where you normally see a URL.

### Skill 2: Clone your repo

These skills are done in a terminal from JupyterLab or RStudio.

1. Copy the URL of your repo. `https://www.github.com/yourname/Test`
2. Open a terminal.
3. Make sure you are at the home directory level. Type this:
    `cd ~`
3. Clone the repo with this command. Replace `yourname` with your username.
    `git clone https://www.github.com/yourname/Test`


### Skill 3: Make some changes and commit your changes

Do step 1 in your editor, JupyterLab or RStudio.

1. Make some changes to the README.md file in the Test repo.
2. Go to the terminal and make sure you are in your Test repo.
    `cd ~/Test`
3. See what has changed. You should see that README.md has changed.
    `git status`
4. Stage the change to the README.md
    `git add README.md`
5. Commit the change.
    `git commit -m "small change"

### Skill 4: Push changes to GitHub / Pull changes from GitHub

To push changes you committed in Skill #3

1. From the terminal, type
    `git push`

To pull changes on GitHub that are not on your local computer:

1. Make some changes directly on GitHub.com and commit
2. From the terminal, type
    `git pull`


### Activity 1

Do steps 1 to 3 in your editor, JupyterLab or RStudio, and steps 4 and 5 in the terminal on the JupyterHub.

1. Make a copy of README.md
2. Rename it to <youname>.md
3. Add some text.
4. Stage and commit the added file.
5. Push to GitHub.

[Show me](https://youtu.be/tvmX41b5pTU)

### Activity 2

Do steps 1-3 on GitHub and step 4 from the terminal on the JupyterHub.

1. Go to your Test repo on GitHub. `https://www.github.com/yourname/Test`
2. Create a file called `test.md`.
3. Stage and then commit that new file.
4. Pull in that new file.

### Activity 3

You can copy your own or other people's repos^[This is different from forking. There is no connection to the original repository.].

1. In a browser, go to the GitHub repository <https://github.com/RWorkflow-Workshops/Week5>
2. Copy its URL.
3. Navigate to your GitHub page: click your icon in the upper right and then 'your repositories'
4. Click the `+` in top right and click `import repository`. Paste in the URL and give your repo a name.
5. Use Skill #1 to clone your new repo to the JupyterHub.

## Clean up after you are done

1. Open a Terminal
2. Type
   
   ```
   cd ~
   rm -rf Test
   rm -rf Week5
   ```


