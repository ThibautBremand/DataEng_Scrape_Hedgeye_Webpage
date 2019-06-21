# Scrape Hedgeye Webpage

This Notebook contains a script corresponding to the exercise evocated in this repo :  
https://github.com/fkchang/Data-Engineer-Applicant-Exercise  

The idea is to scrape this [website's main page's HTML](https://app.hedgeye.com/insights/all?type=insight), using **Beautifulsoup**. Then, we retrieve the top 6 trending articles from this page, and their corresponding URLs. Finally, we can scrape each of the corresponding webpages, using the URLs, in order to obtain all the data we need.  

- Datetime Published
- Headline
- If an author exists (only first author):
  - Image Href
  - Name
  - Twitter Handle (leave blank if not present)
- Content Body HTML

This script has been written in **Python using Jupyter Notebook**.  
The webpages has been scraped using **Beautifulsoup**.  
The results have been stored into a **Pandas dataframe**.  
