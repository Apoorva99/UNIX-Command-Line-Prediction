# **Knowledge Base Creation**

The data obtained after scraping from the website is was passed through an extensive process of pre-processing. The various columns obtained were concatenated, all special characters were removed and the resulting data was stemmed to obtain a uniform data for all the commands. For further removing bias due to large data present in some of the commands, common words 3 characters or less were removed to finally obtain a data ready for synonym pair extraction.
The data was then feeded as input to kb.py and an output knowledge base can be obtained.
