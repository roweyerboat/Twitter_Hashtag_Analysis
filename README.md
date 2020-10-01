# BLM Hashtag Analysis

## Background Information
Over the years, the Black Lives Matter (BLM) movement has gained attention across many platforms. One such platform, Twitter, has been a major place where the message of BLM has been articulated. With the events in May and June of 2020, the deaths of Ahmaud Arbery, Breonna Taylor, and George Floyd, BLM has been in the spotlight more than ever before. With that, there has been a variety of messages about what BLM means and what does it really accomplish. There are some who see it as a new wave of the Civil Rights movement from the 1960s. There are others that consider BLM as a dangerous terrorist organization. In order to sort out the message of BLM, I scraped twitter data from the past 7 years by pulling tweets using twint and searching the hashtag BLM.
I recognize and acknowledge that those that use the hashtag might not be for Black Lives Matter and could even be a critic of it. I felt it was important to gather all that I could to see what rose to the surface when analyzing the text. I also recognize that people have the ability to delete tweets, and so I do not have a full collection of every tweet.
With those acknowledgements, I was able to obtain 220,504 tweets from over 140,000 Twitter users. 

## Libraries Needed
[Twint](https://pypi.org/project/twint/)
[Nest_asyncio](https://pypi.org/project/nest-asyncio/)
[Vader](https://pypi.org/project/vader-sentiment/)
[Textblob](https://pypi.org/project/textblob/)
[Wordcloud](https://pypi.org/project/wordcloud/)
[Nltk](https://pypi.org/project/nltk/)
[Sklearn](https://pypi.org/project/sklearn/)

## The Data
Since it was too large to upload to Github, here are the links for the raw data as well as the clean data
[Raw data](https://drive.google.com/drive/folders/15CaXeeJ8ned9FVKYocex9lPPSOnWqZ5B?usp=sharing)
[Clean data](https://drive.google.com/file/d/1kPipsvCNzIIchTUzEt7NH4nrXxelIJvb/view?usp=sharing)

## Scraping Notebook
The scraping notebook was also too large for github, so here is a [link](https://drive.google.com/file/d/165vOvt2XrFNWwK0m2iZSz35KV4PojxRc/view?usp=sharing) to it

## Repo Files
Tweet Cleaning Notebook - Cleaning the raw data notebook
EDA and Visualization Notebook - Exploratory data analysis and visualizations
Time Series Notebook - Notebook looking at the hashtag over time
Latent Sentiment Analysis - Notebook of the LSA process
Latent Direchlet Allocation - Notebook of the LDA process
BLM_Hashtag_Analysis - Summarization of the whole project

## Findings
Sentiment analysis was inconclusive as a tweet that could be seen as "negative" wasn't necessarily against the BLM movement. Likewise a "positive" sentiment didn't mean the message was for BLM or promoting their values. Therefore I chose to look deeper at the words through Topic Modeling with two methods.

Insert image of top topics from LSA
Insert LDA findings

## Conclusion
Based on the analysis and looking at what continued to rise to the top, the main themes of tweets with the hashtag BLM are about protecting Black lives. Antifa was not included as much as mainstream news outlets assume.
However this is definitely a limited study. It was interesting to see how a sentiment analysis isn't always helpful.
Future work with this and other data sets would be to look at how BLM is portrayed by major news media and see if the words used are similar. An application of this project is to understand the context of the sentiment analysis. 

