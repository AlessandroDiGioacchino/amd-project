
# Algorithms for massive datasets – Project

## Dataset
The projects described in this document refer to the «[Yelp](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset)» dataset, which is published on Kaggle and released under the
CC-BY-SA 4.0 license, with attribution required. Specifically, the projects should be focused on the analysis of the reviews contained in the `yelp_academic_dataset_review.json` 
file (although the remaining files can be used, if needed). Note the dataset is organized as a set of JSON-encoded files, that can be easily transformed into a pandas dataframe, as 
suggested in the dataset web page linked above. You are free to select a suitable subset of cases in the dataset (as the file to be processed is bigger than 5GB), in order to 
balance overall data size and processing time, provided that your code is able to scale up.

## Finding similar items
The task is to implement **from scratch** a detector of pairs of similar tweets, considering the text field of the dataset.
