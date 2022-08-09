# google_news_trends_alerts
Scrape and track the live Google Trend keywords, results, news content, look for the potential keywords match and alert the teams.

Techniques used:
  Category website scraping:Python Beautifulsoup
  Google News and Trends scrapping: Python packages
  Trigger platforms: Gmail, Whatsapp, Slack

Google Trends tracking:
There are two ways Google Trends tracking works
1. Daily search trends
2. Realtime Search Trends

Both of these trends are tracked, pulled and stored by our application, we look for the availability of the Category keywords in the pulled data. And then the respective keywords and content are sent to respective teams through platforms
Also, Google News content is tracked through the same way.


Add the list of the keywords in the following list to track:
lst_words = []
The keywords, topics and contents in the trending topics are scraped and pushed to the respective  teams and content creators in the required format. 
