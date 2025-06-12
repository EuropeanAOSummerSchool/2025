# 2025 European AO Summer School

This repository contains the Jupyter notebooks and simulation configurations for use in the software workshops.

## Downloading
1. Open a terminal/command prompt and navigate to your prefered location to download the files
2. Type `git clone --recurse-submodules https://github.com/EuropeanAOSummerSchool/2025.git` and run the command

The resources needed for each part of the workshop will be downloaded and are contained in the similarly named folder. If you need help installing Python and setting up an environment to run these resources on your own machine please get in touch with the demonstrators or start a discussion [here](https://github.com/orgs/EuropeanAOSummerSchool/discussions/categories/2025-summer-school-help).

## Getting Jupyter notebooks running
To follow this series of notebooks you will need to install a few key packages. This includes:
- aotools
- jupyter

We recommend using the anaconda Python distribution, and installing jupyter and ffmpeg through it:

`conda install jupyter`

`conda install ffmpeg`

Then installing the rest of the packages using pip as it is the easiest way to get up and running, e.g.

`pip install aotools`

Now you should be able to run the command

`jupyter notebook`

This should launch a notebook in your browser which you can then use with the notebooks provided.
