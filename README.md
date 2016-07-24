# TmallScraper
====
## Project Document
====
 * Project Name: RTMartScraper
 * Version: 1.0
 * Author：Guo Zhang,Chen Qian
 * Contributor: 
 * Data: 2016-07-24
 * Python version: 2.7.9 
 * Description: This is a RT-Mart scraper for China's Prices Project
 
----
  

## Project Structure
====
* main.py (main function)
  * RTMartPageScraper.py (a page scraper for RT-Mart APP)
  * geventQueue.py (a gevent queue for RTMartScraper)
  * RTMartCategories.py (the category list for RT-Mart)
  
  * decorator.py (decorators)

* proxiesPool
  * headers.py (user-agents,mobile user-agents and proxies for request headers) 
  * checkedProxies & proxies (IP proxies pool)
  
 -----


## requirements
=====
   * requests
   * bs4
   * gevent
   * pymongo
   
-----   

## CHANGELOG
====
* Version 1.0: 2016-7-24
  * 创建项目
