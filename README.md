# news_scraping

This project is a small attempt to build a sentiment index by scraping some of the most common news sources available on the internet today in such a way that a sentiment index can be easily built.

Essentially there are three scrapers:

1. Google News
  The function google_sentiment() basically goes on google news and scraps the main articles titles and articles pre-ambles. Then it cleans up the articles and count the words used eliminating the most used words.
  Eventually it creates a sentiment analysis based on "# of positive words" / "# of negative words" 
  
Note: if you want to search multiple words you need to add a "+" between them instead of space
  

2. Bloomberg

The function bloom_sentiment() goes on the search function of Bloomberg and scraps the news and politics articles whose link is available in the search results. Then it cleans up the articles and count the words used eliminating the most used words.
  Eventually it creates a sentiment analysis based on "# of positive words" / "# of negative words" 
  
Note: bloomberg is a bit wierd in the way it searches multiple words, and often a "+" between words is no guarantee that the result makes sense.
  
  
 3. Reuters
 
 The function reut_sentiment() goes on the search function of Reuters and scraps the news and politics articles whose link is available in the search results. Then it cleans up the articles and count the words used eliminating the most used words.
  Eventually it creates a sentiment analysis based on "# of positive words" / "# of negative words" 


 
  
  




