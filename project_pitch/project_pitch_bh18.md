---
title: Project pitch
author: José P. Valdés-Herrera, DZNE Magdeburg
date: BrainHack Magdeburg | May 3, 2018
---

# A problem we face {data-background="images/stairs_architecture_secret_curve_0.jpg"}

## We have big data {data-background="images/22588915349_af788736d9_o.jpg"}

- Ultra-near-impossible high res MR
- A couple of long fMRI sessions per participant
- Several Gb MEG recordings

The computer cannot handle it and crashes

## Possible solutions {data-background="images/22588915349_af788736d9_o.jpg"}

- chunk the data and laboriously go through every chunk,
- look for a bigger computer, e.g. cluster

## But I have a cluster! {data-background="images/CSIRO_ScienceImage_11313_The_CSIRO_GPU_cluster_at_the_data_centre.jpg"}

- may need to install software
- may need to re-configure your analysis to make the most out of the hardware

# Two projects, one goal: make it easier to scale and deploy {data-background="images/snails_race_run_road.jpg"}

# Machine Learning with Dask and Neuroimaging Data {data-background="images/haxby_owl_oscar.jpg"}

## Use case {data-background="./images/haxby_owl_oscar.jpg"}

- Researcher wants to do machine learning on a big dataset
- Develop pipeline using Dask/distributed on own computer
- Same researcher then moves all the analysis pipeline to workstation/cluster
- Pipeline takes advantage of more available resources

# Containerized Nipype Pipelines on the Cluster {data-background="images/Piping_pic1.JPG"}

## Use case {data-background="images/eniac.jpg"}

- User runs Nipype-based pipeline in a singularity image
- Computer crashes: too much data
- User decides to use available cluster
    - Copy same singularity image to cluster
    - Run the image
    - It works!

## Another case: QC integration {data-background="images/tacoma_narrows_bridge_collapse.jpg"}

Integrate tools with scanner output: data goes from scanner to QC pipeline

# Join in! {data-background="images/laptop_notebook_clean_hero.jpg"}

## Join in! {data-background="images/laptop_notebook_clean_hero.jpg"}

- No coding experience needed: documentation
- Discuss use cases and solutions
- Synergy with other projects
