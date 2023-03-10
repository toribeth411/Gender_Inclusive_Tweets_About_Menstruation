# Gender-Inclusive Language in Tweets about Menstruation

_By: Tori Stiegman_

### Preliminary Notes
This capstone started as my final project for CS 234: Data, Analytics and Visualization. In the original project, I took a dataset of about 310,000 tweets published between November 10, 2020 and November 10, 2022 and trained a multinomial Naive Bayes classifer to classify them as either gender- inclusive or exclusive, or neither. I expanded this analysis for my data science major capstone project by creating another multinomial Naive Bayes classifier based on more variables, as well as two new classification tree models. I then chose the best classifier by comparing the accuracy, specificity and sensitivity of each of these models. Finally, I used this best classifier to update my original findings and visualizations. 


## Abstract
Because language and social media play critical roles in shaping society's functions, we must strive to use gender-inclusive language while discussing basic bodily processes to promote gender equality and eradicate gender biases. This project looks at how inclusive Twitter users are while tweeting about menstruation by scraping Twitter for English tweets about menstruation and training four different models (two classification trees and two multinomial Naive Bayes classifiers) on variables such as the text of the tweet, the date it was published and the number of likes it recieved in order to classify a larger corpus of tweets as gender- inclusive or exclusive, or neither. It was found that while about 63% of tweets use neither gender-inclusive nor exclusive language, only about 12.5% of tweets about menstruation use inclusive language. This study may imply that while there is a push to use more inclusive language while talking about periods, much more work needs to be done. 


## File Structure
File/Directory | Content
------------- | -------------
sample_results.json | Example file showing the format of the raw data extracted from the Twitter API
sample_period_tweets.csv  | Example file showing the format of the csv file that combines all the raw data from the twitter api
sample_train_clean.csv | Example file showing the format of the cleaned training and testing datasets, as well as the clean full dataset
capstone_jupyter_notebooks | Folder containing .ipynb files that contain all data manipulation and analysis done for this poject
VStiegman_capstone_poster.pdf | PDF file of Data Science Capstone poster 
