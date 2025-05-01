# Datasets
## Dataset Overview
In this work, three publicly available datasets are used to examine the performance of the proposed PT4Rec. 
Here, we provide the links for downloading these datasets for readers to retrieve:

Douban Movie Review Dataset:
Link: https://pan.baidu.com/s/1hrJP6rq#list/path=%2F
Description: The Douban movie review dataset contains user ratings and reviews for movies, which is used to build a user-movie interaction model.

Movielens Dataset:
Link: https://grouplens.org/datasets/movielens
Description: The movie rating dataset contains user ratings for movies, which is used to evaluate the performance of recommendation systems.



## Dataset Usage Instructions
After downloading, please preprocess and load the datasets according to the dataset’s documentation.
When using the datasets for experiments, please ensure compliance with the dataset’s license agreement.

Our process code has been uploaded to the following dir:
```
dataset/
├── douban
│   ├── split.py
├── ml-1M
│   ├── split.py
├── ml-10M
│   ├── split.py
├── README.md
```

