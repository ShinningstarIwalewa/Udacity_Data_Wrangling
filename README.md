# A Data Wrangling Project: WeRateDogs
## By Akolade Sofiyyah Iwalewa
# Introduction
This respository contains a python file which was used for coding, wrangle_report.pdf file which is the 
# Obejective
Wrangle the twitter data (@WeRateDogs) in order to create meaningful analyses and visualizations from the dataset
# Python packages used
- Pandas
- Numpy
- Json
- Request
- Tweepy
- Matplotlib
# Project Methodology
Below are the steps used for this project
- Date Wrangling
 - Data Gathering
 - Data Assessing
 - Data Cleaning
- Data Analysis and Visualization
# Data Gathering
The datasets used for this analysis were gathered from three different sources.
- The twitter_archive_enhanced.csv file was manually downloaded from udacity and uploaded and read in using read_csv().
- The image_predictions.tsv file was downloaded from this URL using the requests library.
- The tweet_json.txt was gotten by querying the Twitter API for additional data using the python tweepy library.
# Data quality issues observed 
 > Below are the quality issues I have observed in the above dataset
- Irrelevant column: Retweet status Id
- Rows with invalid denominator
- Source column is a combination of url and text (only text is needed)
- Incorrect dog names in name column
- Irrelevant column: img_num
- Missing values in the following columns:  in_reply_to_status_id, in_reply_to_user_id, retweeted_status_id, retweeted_status_user_id, retweeted_status_timestamp, expanded_urls columns
- Redundacy in text column
- Incorrect data types in the following colums:  tweet_id, timestamp, dog_stage, p1_dog, p2_dog and p3_dog.
# Insights gotten from the dataset
- Most of the tweets from @WeRateDogs were from an Iphone
- The average tweet likes for dogs in doggo, puppo stage was the highest and it was slightly above 40 thousand likes. This implies that followers @WeRateDogs likes Doggo and Puppo dogs more than any other dogs.
- The ’DoggoPuppo’ dog stage has the highest average rewteet close to 16,000 rewteets as shown by the barchart below. The ’Pupper’ dog stage has the lowest average retweets with approximately 2,000 retweets.
- there is a strong correlation between retweet and favourite tweets (likes). This means tweets that are liked would most likely be retweeted.
- Tweets from an Iphone had the most likes. This could mean that, tweets from an Iphone would most likely get a like. However, there could be other factors
attributed to the likes.

