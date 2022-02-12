# instagram_scraper_and_sentiment_analysis
Instagram Comments Sentiment Analysis
This project is about building automation tool that will go to Instagram post and scrape all the comments.
For this I'll use Selenium. Automated software would go to IG, enter login data provided in config.ini, go to the post and start clicking load more comments button X times(approximately X=num_of_comments/20.
After all comments are loaded, it will find all comments and scrape username + comment.

After this I'll clean the data and prepare it for Sentiment Analysis.
For this I'll use TextBlob, because of easy syntax and good perfromance.
I'll also find the most common words, most common insults, and the most common emojis.

