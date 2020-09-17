# Enabling Data Science with pyTigerGraph
## Code for the Graph+AI World 2020 Conference Presentation

This repository contains the code for the Graph+AI World session *From Dataframes to Graph: Data Science with pyTigerGraph* by Parker Erickson.


## Software Compatibility
Unfortunately, this code will only work on UNIX systems, and they must have Java installed for the Python GSQL interface. This is something we are trying to remedy for future versions of pyTigerGraph.

## Download Data
Download the data [here](https://drive.google.com/file/d/1ySV3cmEUXxtNu32LRlhTiax2teMG9b3Y/view?usp=sharing). The directory structure should be:
```
graphAIWorldDataframeToGraph
                            |-data
                            |     |- artistData.tsv
                            |     |_ etc.
                            |     
                            |-createSchemaAndLoad.ipynb
                            |-genreClassification.ipynb
                            |_ ...
```

## Create Free tgcloud Account
The notebooks assume that you are using a [tgcloud](https://tgcloud.io) instance of TigerGraph. You can create a free instance, and choose "Blank" for the starter kit.

## Python Packages
This repository uses Pandas, pyTigerGraph, Pytorch, and DGL (might be missing a few there). Make sure you have these installed before trying to use the notebooks.

## Graph Machine Learning Resources
Building out [this](https://parkererickson.github.io/graph-ml/) site with many different papers and videos to get you started with graph machine learning.
