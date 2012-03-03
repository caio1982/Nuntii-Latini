Nuntii Latini
=============

Nuntii Latini is a news broadcast in Latin brought to you by some crazy Finnish. Although active for over 20 years they have no public archives with all their texts, you have to buy two or three ridiculously old books with limited news content instead. These are scrapped corpora of news between mid-2010 to 2012, which you can easily analyze with tools such as NLTK.

As of today the corpora contain almost 27.000 tokens (300kb of text). A decent set of corpora contains at least 80.000 usable tokens, so there's plenty of room for improvement, specially trying to scrap even older news posts (pre-June 2010).

To my knowledge, Nuntii Latini only publishes news in Classical Latin. Do no try to run ecclesiastical parsers or anything like that on these files, unless you know what you're doing.

Format
------

The following "tags" are used throughout the corpora, so you will need to ignore them when doing your natural language processing magic:

* TITLE: the title of broadcast of the day
* PUBLISHED: metadata about its publishing date and time
* HEADER: title of secondary news of the day
* PARAGRAPH: the first without a header is for the main article, others appear after a header only
* AUTHOR: the name of the person who published the article

All corpora are in plain texts without blank lines.

Contributing
------------

I'd really love to convert this scrapper into one written in Python, using Scrapy.org (which I actually used in the very beginning but doing it in shell was way faster). Wanna help me to do it? :-)