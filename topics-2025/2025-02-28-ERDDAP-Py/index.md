# ERDDAP in Python

**Author:** NOAA CoastWatch, modified by Daisy Shi (OceanWatch Pacific)



## Tutorials

Link to training repo in CoastWatch org: [CoastWatch tutorials](https://github.com/coastwatch-training/CoastWatch-Tutorials)

* [Satellite data matchup track locations](erddap_intro_satellite_matchup_track_2_options.html) This tutorial shows how to use ERDDAP data to get SST and CHL along a sea turtle track.
* [ERDDAP and xarray](erddap_xarray.html) This tutorial shows an example of creating a data cube from a ERDDAP data collection and creating spatial and temporal means.

The [erddapy Python package](https://ioos.github.io/erddapy/) helps you search and do common tasks with ERDDAP servers. See the tutorials on the IOOS CodeLab: <https://ioos.github.io/ioos_code_lab/search.html?q=import+erddapy>

## How to clone the git repository 

Never cloned the NOAAHackDays repo?

```
cd ~
git clone https://github.com/nmfs-opensci/NOAAHackDays
```

Have cloned it but need to update? This is going to destroy any changes that you made to the repo to make it match the current state of the repo on GitHub.

```  
cd ~/NOAAHackDays
git fetch origin
git reset --hard origin/main
```
