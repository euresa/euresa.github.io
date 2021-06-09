---
layout: post
---

# Wikipedia Web Scraping

Over COVID, I've become increasingly more interested in NLP techniques and want to start training some models on corpuses I've gathered myself. In order to accomplish this, I created a short Python script to help me scrape data from Wikipedia pages. I'd also like to see how different topics in Wikipedia seem to be related to each other, so I've layed the groundwork for taking basic random walks across a network of Wikipedia pages. 
The code can be found [here.](https://nbviewer.jupyter.org/github/euresa/PythonProjects/blob/main/Wikipedia_Scraping/wiki_scraper.ipynb)  

I opted to carry out most of the NLP of the Wikipedia HTML myself as opposed to heavily relying on a package already written. I'm sure there are easier ways to scrape Wikipedia pages, but I enjoyed developing my own functions. In the future, I hope to use this script to obtain training data for some ML language models.