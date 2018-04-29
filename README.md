# economist-scrapy
scrapy spider and postgresql pipline for economist

diligent spider for [EcoArchive](https://www.ecorkv.cn/)

# nltk
article summary is generated by nltk, you'll have to install nltk package and its corpora data: brown, averaged_perceptron_tagger and punkt first

# crawl and storage
use postgresql as storage, assuing that you have a postgresql service running on localhost and default port. set your own（db, uername, password）in setting.py

use crontab tools to add crawl job each week