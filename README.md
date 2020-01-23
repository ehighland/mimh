### Method
I gathered 3000 tweets each for the queries "mental health" and "mental illness".
To this end, I used the Python library GetOldTweets3 to gather extra data. With this library, I am not confined to the past week. I have set the time frame from Jan 1st to Jan 22nd. I have also elected to only get tweets in English.
After I had gathered tweets, I did some data cleaning in R. I reduced the csv files from 12 features to only 3: date, user id, and the text of the tweet.

### Files
Tweets were gathered using the bash script file mimh.sh.
Data cleaning process is shown in MIMH.Rmd.
The original files are: mentalillness.csv and mentalhealth.csv
The cleaned files are: mentalillness-clean.csv and mentalhealth-clean.csv

