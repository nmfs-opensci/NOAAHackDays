---
title: Quick Start
---

For those already familiar with Jupyter Lab and unix.

### GitHub Account

A GitHub account is required to gain access to the JupyterHub and to clone the tutorials used in the Hackhours.

How do I get the tutorials into the JHub? 

* You can upload files.
* Easiest is probably cloning into the hub. Open a terminal and type
```
cd ~
git clone <url of the github repo>
```

**Authenticating to GitHub** You will need to do this to be able to push to GitHub. See [git authentication](https://nmfs-opensci.github.io/NOAAHackDays/topics-skills/02-git-authentication.html).

### Earthdata Login Account

For content that uses the NASA [Earthdata](https://www.earthdata.nasa.gov/) repository, you will need an Earthdata Login account. Please visit [https://urs.earthdata.nasa.gov](https://urs.earthdata.nasa.gov) to register and manage your Earthdata Login account. This account is free to create. Please jot down your username and password, as you need to enter it in the tutorials.


### When done, please stop the JupyterHub

If you are in Jupyter lab in the browser:

- File > Hub Control Panel > Stop my server

If you are in RStudio and you still have the Jupyter lab tab open in your browser:

- Go to the Jupyter lab tab
- File > Hub Control Panel > Stop my server

If you are in RStudio and you do not have the Jupyter lab tab open in your browser because you closed that tab:

- Go to the url `https://<jupyterhub url>/user/<your username in the hub>/lab/` That will open the Jupyter lab tab
- File > Hub Control Panel > Stop my server
