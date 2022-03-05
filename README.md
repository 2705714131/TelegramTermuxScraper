# TelegramTermuxScraper
How To Install and Use ↓

$ pkg install -y git python

$ git clone https://github.com/2705714131/TelegramTermuxScraper

$ cd TelegramTermuxScraper

Install requierments ↓

$ python3 setup.py -i

setup configration file -API Rec
https://my.telegram.org/auth?to=apps
 ( apiID, apiHASH ) ↓

$ python3 setup.py -c

To Genrate User Data ↓

$ python3 scraper.py

Send Bulk sms To Collected Data ↓

(members.csv is default if you changed name use it)

$ python3 smsbot.py members.csv

or $ python3 smsbot.py Other_members.csv

Add users to your group ↓

$ python3 adder.py

or python3 add2group.py members.csv

Update Tool ↓

$ python3 setup.py -u

errors manual ↓

https://core.telegram.org/api/errors
