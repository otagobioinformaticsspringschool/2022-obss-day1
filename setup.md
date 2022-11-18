---
title: Setup
---


This workshop is designed to be conducted on the [NeSI](https://www.nesi.org.nz) compute infrastructure. All software and data is already set up for you to use during the workshop.

Running the workshop locally on your own computer will involve installing the required programs and downloading the example data. Some software packages may not work on all operating systems. Below are the requirements for running locally.


## Software

This software is required at a minimum in order to follow through the lessons. Jupyter labs is used in the lessons, but for running locally it is recommended to use the stand-alone programs.

In order to run the workshop on your own computer you will need to ensure you installed:

- A UNIX shell such as BASH
    - [install instructions](https://carpentries.github.io/workshop-template/#setup)
- R and RStudio. (use Rstudio in place of the R notebooks from Jupyter)
    - [install instructions](https://carpentries.github.io/workshop-template/#setup)

## Data

In order to replicate the directory structure of the workshop, in bash run these commands:

```bash
mkdir -p ~/obss_2021/intro_r ~/obss_2022/intro_bash

curl -L -o ~/obss_2022/intro_bash/shell_data.tar.gz https://figshare.com/ndownloader/files/14417834
tar -xzf ~/obss_2022/intro_bash/shell_data.tar.gz


curl -L -o ~/obss_2022/intro_r/combined_tidy_vcf.csv https://ndownloader.figshare.com/files/14632895
```

{% include links.md %}
