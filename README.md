<p align="center">
  <img src="https://raw.githubusercontent.com/Subhradeep00/TeleGram-Scraper/master/.image/20191203_205322.jpg" width="470" height="150">
</p>

<p align="center"><img src="https://img.shields.io/badge/Version-3.1-brightgreen"></p>
<p align="center">
  <a href="https://github.com/Subhradeep00">
    <img src="https://img.shields.io/github/followers/Subhradeep00?label=Follow&style=social">
  </a>
  <a href="https://github.com/Subhradeep00/TeleGram-Group-Scraper">
    <img src="https://img.shields.io/github/stars/Subhradeep00/TeleGram-Group-Scraper?style=social">
  </a>
</p>
<p align="center">
  Telegram Group Scrapper
</p>
<p align="center">
</p>

---

## • API Setup
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

## • How To Install and Use

`$ pkg install -y git python`

`$ git clone https://github.com/Subhradeep00/TeleGram-Scraper.git`

`$ cd TeleGram-Scraper`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Genrate User Data

`$ python3 scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* Update Tool

`$ python3 setup.py -u`
