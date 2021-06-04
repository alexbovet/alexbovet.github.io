---
permalink: /codes_and_data/
title: Codes and data
classes: wide

---

## Temporal networks

The wild mice contact network collected by Barbara Konig and Anna Lindholm and analysed in our paper [Flow stability for dynamic community detection](https://arxiv.org/abs/2101.06131) is available on Zenodo here: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4725155.svg)](https://doi.org/10.5281/zenodo.4725155)

The code for our paper [Flow stability for dynamic community detection](https://arxiv.org/abs/2101.06131) is available on github [here](https://github.com/alexbovet/flow_stability).

## Anomaly Detection

The code for our algorithm MADAN published in the paper: Gutiérrez-Gómez, L. Bovet, A. & Delvenne, J.-C. [Multi-scale Anomaly Detection on Attributed Networks](https://aaai.org/ojs/index.php/AAAI/article/view/5409).
Proceedings of the AAAI Conference on Artificial Intelligence. Vol 34 No 01: AAAI-20 Technical Tracks 1 (2020)
is available [here](https://github.com/leoguti85/MADAN).

Ipython notebooks for reproducing the [toy example](https://github.com/leoguti85/MADAN/blob/master/toy_example.ipynb) and [case study](https://github.com/leoguti85/MADAN/blob/master/Case_of_study_Disney.ipynb) of the papers are also provided.


## Twitter Analysis

These softwares: [hydrator](https://github.com/DocNow/hydrator), [twarc](https://github.com/DocNow/twarc) and [tweepy](http://www.tweepy.org/) can be used to “rehydrate” the tweet_IDs, i.e. download the full tweet objects using the tweet_IDs.


### Fake news influence

The dataset containing the retweet networks and the tweet IDs that have a URL directing toward a news outlet website of the corresponding media category is available on OSF here: [doi.org/10.17605/OSF.IO/J6PKS](https://doi.org/10.17605/OSF.IO/J6PKS)

It is used in our paper:
Bovet, A. & Makse, H. A. [Influence of fake news in Twitter during the 2016 US presidential election](https://www.nature.com/articles/s41467-018-07761-2). Nat. Commun. 10, 7 (2019).

The code used for the analysis of this dataset is also available on OSF [doi.org/10.17605/OSF.IO/E4TVH](https://doi.org/10.17605/OSF.IO/E4TVH).

The curated list of website spreading fake and extremely biased news used in our paper is available [here](https://github.com/alexbovet/opensources).

### Opinion mining

This dataset contains the tweet IDs of 170 million tweets from 11 million users posting about the election between June 1st 2016 until November 9th 2016.

It is used in our paper:
Bovet, A., Morone, F. & Makse, H. A. [Validation of Twitter opinion trends with national polling aggregates: Hillary Clinton vs Donald Trump](https://www.nature.com/articles/s41598-018-26951-y). Sci. Rep. 8, 8673 (2018).

See [README](https://hmakse.ccny.cuny.edu/wp-content/uploads/2020/05/README.txt) file and [dataset](https://lipc23.engr.ccny.cuny.edu/f/c2a9745179b44add91ed/?dl=1).

The code of algorithm that we developed is available [here](https://github.com/alexbovet/twitter_opinion_mining) and
the following [ipython notebook](https://github.com/alexbovet/twitter_opinion_mining/blob/master/Twitter_opinion_mining_example_run.ipynb) explains how to use it.


### Twitter social network and sentiment analysis

You will find [here](https://github.com/alexbovet/network_lesson) the ipython notebooks for the lecture I gave at  [The Graduate Center of the City University of New York](https://gc.cuny.edu/Home) in 2017.

The notebooks also cover the basics about how to use tweepy to connect to the Twitter API and collect tweets.

