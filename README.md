# WeRateDogs-Twitter-Archive-Data-Wrangling-Project
This project performs Data Wrangling on WeRateDogs twitter archive. In this project, a couple of wrangling efforts were used to wrangle the WeRateDogs Twitter archive datasets. The data wrangling steps involves Data Gathering, Data Assessing, Data Cleaning, Data Analyzing and Visualizations. Three different datasets will be gathered, assessed, cleaned, merged into one and analyzed.

# Datasets
The Twitter Archive file (twitter_archive_enhanced.csv) was provided by the Udacity and it was manually downloaded and read into a pandas dataframe. The WeRateDogs Enhanced Twitter Archive contains about 5000+ tweets and over 2300+ tweets were successfully extracted from the twitter archive between November 15, 2015 and August 1, 2017. After assessing and cleaning the data, over 1900+ tweets were structured into one dataframe.

The tweets image prediction file (image_predictions.tsv) is hosted on Udacity’s servers and was downloaded programmatically using the Requests Library from this url: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_imagepredictions/image-predictions.tsv

The Tweets JSON file was downloaded programmatically by querying the Twitter API using the Tweepy library. The retweet count and favorite count were extracted from this file and read line by line into pandas dataframe.

# Conclusion
In the course of undertaking this Data wrangling project, a number of data wrangling processes have been used, thereby exploring python and its libraries. Data wrangling is an essential skill for all Data analysts today, therefore this project presented a sterling opportunity to hone my data wrangling skills.
