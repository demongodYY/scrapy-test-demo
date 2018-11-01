


# 测试scrapy爬虫

## 数据源网站 
http://quotes.toscrape.com/

## windos环境下需要
    $ pip install pypiwin32
    https://www.lfd.uci.edu/~gohlke/pythonlibs/#twisted 中下载对应 python 版本的 twisted ,然后 
    $ pip install xx/twisted-xxx.whl

## 运行本项目
    $ pip install scrapy
    $ scrapy crawl toscrape-xpath -o test1.json

## 创建新的 scrapy 项目
    $ scrapy startproject tutorial