# Udacity_Wrangle_and_Analyse_Data

## 1 Wrangle Report
The project focused on wrangling data from the ’WeRateDogs’ account on twitter. The efforts put
into the wrangling process are highlighted below:
- Data Gathering
- Assessing the Data
- Cleaning the Data
- Analysing the Data
- Visualising the Data

## 1.1 Data Gathering
The data was gathered from three different sources: 1. A twitter-archived csv file containing
information about the kind of dog per dogsize, wheter the tweet was a retweet and the day and
time of the tweet. it was then loaded into a pandas dataframe
2. An Image predictions tsv file that was downloaded programmatically using the requests
library of which a folder was created for and the file was loaded into a pandas dataframe
3. Additional twitter API data, an alternative approach was used as made available to me via
the tweet-json text file and the code provided to load the data was used.

## 1.2 Assessing the Data
All data were assessed via two main approaches, the virtual assessment and the programatic assessment which required the use of some pandas functions to describe, summarise the data. The
quality issues found were documented as well as the tidyness issues.

## 1.3 Cleaning the Data
Copy’s of the original dataframes were created and the copied dataframe was then cleaned after
assessment to resolve both quality and tidyness issues found. Aftwards the three dataframes were
combined and saved into one master csv file. This is an important step as to ensure we are able to
find the right insights while analysing the data.

## 1.4 Analysing the Data
The data was further analysed using a number of pandas methods as well as other python functions to find notable insights within the data.

## 1.5 Visualising the Data
After analysis the insights found were then translated into visuals using charts and graphs by
pandas plot function. Visualising this insights is an important step in communicating them to the
various stakeholders
