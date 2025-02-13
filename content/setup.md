---
title: Quick Start
---

For those already familiar with JupyterLab and unix.

### GitHub Account

A GitHub account is required to gain access to the JupyterHub and to clone the tutorials used in the Hackhours.

How do I get the tutorials into the JupyterHub? 

* You can upload files.
* Easiest is probably cloning a repo into the hub. See the JupyterHub Skills section if you do not know how to do this.

### Authenticating to GitHub

This is a little different on the JupyterHub. See [git authentication](https://nmfs-opensci.github.io/NOAAHackDays/topics-skills/02-git-authentication.html).

For content that uses the NASA [Earthdata](https://www.earthdata.nasa.gov/) repository, you will need an Earthdata Login account. Please visit [https://urs.earthdata.nasa.gov](https://urs.earthdata.nasa.gov) to register and manage your Earthdata Login account. This account is free to create. Please jot down your username and password, as you need to enter it in the tutorials.


### When done, please stop the JupyterHub

If you are in JupyterLab in the browser:

- File > Hub Control Panel > Stop my server

If you are in RStudio and you still have the JupyterLab tab open in your browser:

- Go to the JupyterLab tab
- File > Hub Control Panel > Stop my server

If you are in RStudio and you do not have the JupyterLab tab open in your browser because you closed that tab:

- Go to the url `https://<jupyterhub url>/user/<your username in the hub>/lab/` That will open the JupyterLab tab
- File > Hub Control Panel > Stop my server
