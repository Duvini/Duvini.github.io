# HOME-BIO

Despite the large amount of metagenomic shotgun data produced, there is a lack of a comprehensive and easy-use pipeline for data analysis that avoids annoying and complicated bioinformatics steps. Here, we present **HOME-BIO** (sHOtgun MEtagenomic analysis of BIOlogical entities), a modular and exhaustive pipeline for analysis of biological entity estimation, specifically designed for shotgun sequenced clinical samples. HOME-BIO analysis provides a comprehensive taxonomy classification by querying different source database and carry out the main steps in the metagenomic investigation.

HOME-BIO is a dockerized solution for metagenomics. Inside a DOCKER image, we installed UBUNTU with Python 3.8 and Anaconda 3 (V. 2020/02). Inside an anaconda base environment, we installed two common metagenomics software, [KAIJU](http://kaiju.binf.ku.dk/) and [KRAKEN 2](https://ccb.jhu.edu/software/kraken2/), and other mandatory software for the pipeline. For more details, please read our paper here (link)


## 1 - DOCKER & PYTHON INSTALLATION

To use our pipeline, it is mandatory to install and run DOCKER (https://hub.docker.com/) and to install and use Python 3.

- [Here](https://hub.docker.com/search?q=&type=edition&offering=community) you can find the correct version of DOCKER for your OS and all the info about how to install and run DOCKER.

- To install Python 3 there are several options depending on your OS:

