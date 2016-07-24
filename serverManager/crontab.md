# crontab

* crontab -e
* 
  * minute hour \* \* \* sh /home/ubuntu/TmallScraper/serverManager/rtmartscraper.sh >> /home/ubuntu/log/rtmartscraper.log 2>&1
  * minute hour \* \* \* sh /home/ubuntu/TmallScraper/serverManager/rtmartrar.sh >> /home/ubuntu/log/rtmartscraper.log 2>&1
  * minute hour \* \* \* sh /home/ubuntu/TmallScraper/serverManager/rtmartemail.sh >> /home/ubuntu/log/rtmartemail.log 2>&1