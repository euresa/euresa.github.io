---
layout: post
---

# Wikipedia Web Scraping

I recently saw a data science internship with the US Embassy in London requesting that individuals interested in the position write a script in Python capable of scraping a Wikipedia pages. The posting specified that the script should match plain text data and hyperlinks to the titles of each of the subsections of the page. Although I've dabbled with web scraping Python modules in the past (such as BeautifulSoup), I'd never really had a concrete objective to work toward. However, the challenge presented in the internship listing sounded quite interesting to me, so I decided to go for it!

I opted to carry out most of the NLP of the Wikipedia HTML myself as opposed to heavily relying on a module already written. I'm sure there are easier ways to scrape Wikipedia pages (and web pages in general), but I enjoyed playing around with my own functions in order to solidly understand how the code is working. In the future, I hope to use this script to obtain training data for some ML models. 