---
title: Earthdata Login
---


NASA data are stored at one of several Distributed Active Archive Centers (DAACs). If you're interested in available data for a given area and time of interest, the [Earthdata Search](https://earthdata.nasa.gov/) portal provides a convenient web interface.

## Why do I need an Earthdata login?

To programmatically access NASA data from within your Python or R scripts, you will need to enter your Earthdata username and password.

## Getting an Earthdata login

If you do not already have an Earthdata login, then navigate to the [Earthdata Login](https://urs.earthdata.nasa.gov/) page, a username and password, and then record this somewhere for use during the tutorials:

## Configure programmatic access to NASA servers

Run the following commands on the JupyterHub:

::: {.callout-important}
In the below command, replace `EARTHDATA_LOGIN` with your personal username and
`EARTHDATA_PASSWORD` with your password
:::

```
echo 'machine urs.earthdata.nasa.gov login "EARTHDATA_LOGIN" password "EARTHDATA_PASSWORD"' > ~/.netrc
chmod 0600 ~/.netrc
```
