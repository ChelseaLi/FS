FS
==
scrapy startproject XXX
cd XXX

[adjust] items.py

[add under XXX/spiders] XXX_spider.py
[adjust] allowed _domains, start_urls, xpath

[adjust] pipeline.py
[adjust] setting.py

scrapy crawl XXX -o items.json

unzip \*.zip
