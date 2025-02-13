---
title: Quick Start
---

### Sign up

**NOAA staff**: Fill out this short form [NOAA staff access](https://docs.google.com/document/d/15Wu28DGDKNsdQmW5yuFd3JJuUSn91HFxCEb3dqPxYcs/edit?usp=sharing) to give us the 
required credentials and information to get you on the hub.

Once we have your information, within the next day or two we will invite you to the NMFS Openscapes GitHub organization. You will receive an email when we do this from GitHub **at the email you have linked to your GitHub profile**. Please accept this invitation within 7 days or it will disappear and we will need to resend it. Your membership on that GitHub team provides you with access to the JupyterHub.

### Policies for use

* This is for learning, participating in trainings and working on pilot projects (testing)
* No BII or PII whatsoever or confidential data
* After 30 days of not logging in, you account will be deleted and your user directory removed. You can log back in, but your data will be gone. Make sure to back up, download or pull the data and code you are working on.
* Clean up after you are done working on something. So if you clone a repo to test something, delete the repo if you don't need it.

**Non-NOAA participants in a workshop or event**: the workshop organizers will provide instructions for access during the event.

### Orientation

{{< video https://youtu.be/SEvHUZI6aj4 >}}

### GitHub Account

A GitHub account is required to gain access to the JupyterHub and to clone the tutorials used in the Hackhours.

### How do I files into the JHub? 

* You can upload files.
* Easiest is probably cloning a repo into the hub. See the JupyterHub Skills section if you do not know how to do this.

### Authenticating to GitHub

This is a little different on the JupyterHub. See [git authentication](https://nmfs-opensci.github.io/NOAAHackDays/topics-skills/02-git-authentication.html).

### Earthdata Login Account

For content that uses the NASA [Earthdata](https://www.earthdata.nasa.gov/) repository, you will need an Earthdata Login account. Please visit [https://urs.earthdata.nasa.gov](https://urs.earthdata.nasa.gov) to register and manage your Earthdata Login account. This account is free to create. 

### When done, please stop the JupyterHub

If you are in Jupyter Lab in the browser:

- File > Hub Control Panel > Stop my server

If you are in RStudio and you still have the Jupyter lab tab open in your browser:

- Go to the Jupyter Lab tab
- File > Hub Control Panel > Stop my server

If you are in RStudio and you do not have the Jupyter lab tab open in your browser because you closed that tab:

- Go to the url `https://<jupyterhub url>/user/<your username in the hub>/lab/` That will open the Jupyter lab tab
- File > Hub Control Panel > Stop my server
