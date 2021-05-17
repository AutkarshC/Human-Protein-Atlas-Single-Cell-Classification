# Goals

Feature engineering: create new features from the raw data

Supervised learning models: Choose 2 supervised learning models 

Advanced models: choose 1 from XGBoost or Neural Network or Deep learning to build your supervised learning models

# For dataset download from below URL:

https://www.kaggle.com/c/hpa-single-cell-image-classification/overview


# Human Protein Atlas - Single Cell Classification Description

There are billions of humans on this earth, and each of us is made up of trillions of cells. Just like every individual is unique, even genetically identical twins, scientists observe differences between the genetically identical cells in our bodies.

Differences in the location of proteins can give rise to such cellular heterogeneity. Proteins play essential roles in virtually all cellular processes. Often, many different proteins come together at a specific location to perform a task, and the exact outcome of this task depends on which proteins are present. As you can imagine, different subcellular distributions of one protein can give rise to great functional heterogeneity between cells. Finding such differences, and figuring out how and why they occur, is important for understanding how cells function, how diseases develop, and ultimately how to develop better treatments for those diseases.

To see more, start with less. That may seem counterintuitive, but the study of a single cell enables the discovery of mechanisms too difficult to see with multi-cell research. The importance of studying single cells is reflected in the ongoing revolution in biology centered around technologies for single cell analysis. Microscopy offers an opportunity to study differences in protein localizations within a population of cells. Current machine learning models for classifying protein localization patterns in microscope images gives a summary of the entire population of cells. However, the single-cell revolution in biology demands models that can precisely classify patterns in each individual cell in the image.

The Human Protein Atlas is an initiative based in Sweden that is aimed at mapping proteins in all human cells, tissues, and organs. The data in the Human Protein Atlas database is freely accessible to scientists all around the world that allows them to explore the cellular makeup of the human body. Solving the single-cell image classification challenge will help us characterize single-cell heterogeneity in our large collection of images by generating more accurate annotations of the subcellular localizations for thousands of human proteins in individual cells. Thanks to you, we will be able to more accurately model the spatial organization of the human cell and provide new open-access cellular data to the scientific community, which may accelerate our growing understanding of how human cells functions and how diseases develop.

This is a weakly supervised multi-label classification problem and a code competition. Given images of cells from our microscopes and labels of protein location assigned together for all cells in the image, Kagglers will develop models capable of segmenting and classifying each individual cell with precise labels. If successful, you'll contribute to the revolution of single-cell biology!

The scientific journal Nature Methods is interested in considering a paper discussing the outcome and approaches of the challenge. The Human Protein Atlas team, led by Professor Emma Lundberg, would like to invite top performing teams to join as co-authors in writing this paper. Please follow the discussion forum for more details on how you can help.

# Data Description

You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

# File descriptions

sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.

test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.

sample_submission.csv - a sample submission file in the correct format.

items.csv - supplemental information about the items/products.

item_categories.csv  - supplemental information about the items categories.

shops.csv- supplemental information about the shops.

# Data fields

ID - an Id that represents a (Shop, Item) tuple within the test set

shop_id - unique identifier of a shop

item_id - unique identifier of a product

item_category_id - unique identifier of item category

item_cnt_day - number of products sold. You are predicting a monthly amount of this measure

item_price - current price of an item

date - date in format dd/mm/yyyy

date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33

item_name - name of item

shop_name - name of shop

item_category_name - name of item category

This dataset is permitted to be used for any purpose, including commercial use.
