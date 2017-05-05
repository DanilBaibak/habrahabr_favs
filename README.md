# Predict how many favorites will achieve an article, knowing it's title and publication time

## Overview
It's the competition [kaggle inclass](https://inclass.kaggle.com/c/howpop-habrahabr-favs). The task is to predict 
how many favorites will achieve an article from the site [habrahabr](https://habrahabr.ru/), based on knowledge
of the title and publication time. The training and testing dataset you can download 
from the [competition page](https://inclass.kaggle.com/c/howpop-habrahabr-favs-lognorm/data). Current solution let 
you achieve 0.62294 on the public leaderboard.

## Environment
Python 3.5, jupyter notebook, scikit-learn

## Installation
For installation please use [conda](http://conda.pydata.org/docs/using/index.html). Just run:
```sh
make init
```
After the installation was done successfully, activate your enviroment:
```sh
source activate habr
```
> For using **conda** and **environments**, 
please read full documentation of [conda](http://conda.pydata.org/docs/using/index.html).

## Usage
After activate source, run `jupyter notebook main.ipynb`. The *main.ipynb* is precompiled, so you can have a look
without instalation.

