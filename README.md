This is a webscraping project that I conducted for a research article on ISIS propaganda and terrorist attacks. One of the variables in the project was media portrayal of ISIS attacks.

The webscraping script does the following:
1. It searches the BBC website for all the articles containing keywords such as "ISIS" and "bombs", "airstrikes", "drones", and names of specific countries between April 1, 2013 and December 31, 2016

2. It saves all the URLs, dates, and titles

3. It further checks if the keywords "airstrikes" and "Islamic State" are present within the body of the article

4. From those articles that meet the previous condition, it extracts all the sentences that contain the keywords "air strike", "bomb", and the names of countries.

5. The end result is an excel spreadsheet with the following variables: -country -article_url -date -Title article -relevant sentences from that article
