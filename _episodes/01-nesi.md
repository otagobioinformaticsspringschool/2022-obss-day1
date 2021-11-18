---
title: "Introduction to NeSI"
teaching: 15
exercises: 15
questions:
- "How can I log onto Jupyter hub notebooks hosted on NeSI"
objectives:
- "Understand how to log into Jupyter hub on NeSI"
keypoints:
- "NeSI provides interactive access through Jupyter hub"
---

# Introduction to NeSI

[Accessing Jupyter on NeSI](https://github.com/GenomicsAotearoa/metagenomics_summer_school/tree/master/Access_NeSI_platforms/4_Access_HPC_via_Jupyterhub)

>**WARNING**- We **do not recommend** using Internet Explorer to accss [NeSI JupyterHub](https://jupyter.nesi.org.nz/hub/login)

1. Follow https://jupyter.nesi.org.nz/hub/login
2. Enter NeSI username, HPC password and 6 digit second factor token
![Jupyter hub login window](../fig/Login_jupyterhubNeSI.png)
3. Choose server options as below OR as required for the session
>Project code should be **nesi02659** (select from drop down list), Number of CPUs and memory size will remain unchanged. However, select the approriate **Wall time** based on the projected length of a session
![Server options for NeSI Jupyter hub](../fig/ServerOptions_jupyterhubNeSI.png)
4. Jupyter Launcher screen
 ![Jupyter launcher screen](../fig/ga-vl01jupyterhunNeSI.png)

[Trouble shooting Jupyter](https://github.com/GenomicsAotearoa/metagenomics_summer_school/tree/master/Access_NeSI_platforms/5_Jupyter_Troubleshooting)


## Getting data onto/off of NeSI

For small files (a few megabytes) you can use the upload button on Jupyter hub in the file explorer pane. For downloading (small files) use the navigation pane to find the file you would like, right click and then select to download.

Both upload and download through Jupyter Hub is done through the browser and not recommended for larger files ( >100 MB)


For moving larger data onto or off of NeSI the [use of globus is recommended](https://support.nesi.org.nz/hc/en-gb/articles/360000576776-Data-Transfer-using-Globus-V4).

<!-- include a schematic of the file system and how the workshop directories will be laid out-->

{% include links.md %}

