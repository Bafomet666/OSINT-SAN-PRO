# OSINT-SAN-Framework

Framework aimed at obtaining data and de-anonymizing users. The tool uses a large number of APIs. Now the tool is being finalized, some functions may not work correctly.

Tool adapted for: Kali Linux * Parrot

PRO Version https://www.youtube.com/watch?v=5oFaQADPtnc

![alt tag](https://github.com/Bafomet666/screen/blob/main/LOGOup.png)

----

To work you need an API

The name of the API and the sites to get them.

    API for getting information about the number https://numverify.com
 
    API for getting whois information https://ipstack.com

    Shodan API https://www.shodan.io

    Checking on CMS https://whatcms.org/API

    Gmap for gui https://developers.google.com/maps/documentation

    VirusTotal free checker service https://developers.virustotal.com/v3.0/reference

    Hunter.io API for @mail info https://hunter.io/api

    ZoomEye API, login is carried out by authorization in the tool itself https://www.zoomeye.org

    Torrent API https://iknowwhatyoudownload.com/en/api/

    CMS detect https://whatcms.org

    Be sure to register the API in settings.py
  
  
  ### Dependencies. ![Альтернативный текст](https://camo.githubusercontent.com/d4d0378438eebbdfdf98948d518a47cb34bd241b3c836aaae47255a64f2c3bbe/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e372532422d627269676874677265656e)

  Once you've entered all your APIs, you need to install the dependencies:

  sudo pip3 install -r requerements.txt

  In complex modules, you will be presented with the choice of additional installation of modules.
  
  
  
Using:

Run with the command: python3 osintsan.py

The password and login are stored in our public telegram.

The tools run in two modes:

If you want non-root functions [They are in green line], run a terminal: python3 osintsan.py
  
If you need root functions [They are green red], run a terminal: sudo python3 osintsan.py

Official public https://t.me/osint_san_framework

![alt tag](https://github.com/Bafomet666/screen/blob/main/login.png)


After successful authorization, a menu with tools will be available to you.

---

### Functionality:

#### Function [01]
Checking IP addresses in Shodan and Censys for leaks.

#### Function [02]
Working with a domain name.

     Reverse
     Subdomian
     NsLookup
     CMS Detect
     Port scan
     Bruteforse
     ClickJaking
     Cors
     Host Header Injection
     Header
     Crawler

#### Function [03]
Receiving data about a mobile number.

#### Function [04]
High Resolution DNS Map

#### Function [05]
Calculating the location of the photo, extracting geolocation from the photo.


#### Function [06]
Searching for images in google and yandex.

#### Function [07]
Checking the server or IP address for HoneyPot

#### Function [08]
Mac address info, with a 40% probability will also show geolocation.

#### Function [09]
IP geolocation on GUI maps. Input data can be either an IP address or a domain.

#### Function [10]
Check what the victim is downloading via torrent at the moment.
 
#### Function [11]
OSINT Instagram.

#### Function [12]
DNS info, a huge pack of information.

#### Function [13]
Collecting @mail addresses from sites. The censys API is used.

#### Function [14]
Connecting via android debug bridge.

#### Function [15]
Big bro 8.0 geolocation mode.

#### Function [16]
Bulk data dump with Shodan. Works via API

#### Function [17]
Graphical monitoring of your local network GUI

#### Function [18]
Checking all plugins and modules.

#### Function [19]
Search by nickname maigret.

By soxoj https://github.com/soxoj/maigret

#### Function [20]
The function opens sites for identification by face.

#### Function [21]
OSINT Wikipedia

#### Function [22]
ip logger

#### Function [23]
Anonymous mail

#### Function [24]
Bafomet + Password Database
Now the database contains 1.9 billion passwords. Everything is broken down in parts, so that it would be convenient to download. Passwords for various tasks.

#### Function [25]
Bringing the Beff-XSS website online

First you need to press 1. This is the online option.
Then you will see instructions for setting ngrok to the position (start --all for 4 links) After you run ngrok in full mode and start the program.

After you will be asked to enter links, enter up to http, https in this format:

     f19d35259оaff5.ngrok.io always first on port 80
     
     f19d3c96533ff5.ngrok.io then on port 3000
     
Setting styles for the site. You need to go to the "OSINT SAN" folder and copy everything there from the "Beef Styles" folder to the / var / www / html directory

If suddenly you do not have access to copy styles in beef html, Do:
         
         sudo chmod 777 / var / www / html

#### Function [26]
Our large OSINT CIS community

#### Function [27]
Large pack of OSINT information

#### Function [28]
Open Maltego, just opens maltego.

#### Function [29]
Bulk data dump with ZoomEye. Analogue of shodan.

#### Function [30]
Deanonymization of a hacker with his own link ngrok, this is a regular parser

----

Enjoy your use.

[License] (https://github.com/Bafomet666/OSINT-SAN/blob/main/LICENSE)

You should only use this framework for legal verification agreed by both parties,
or for educational purposes, I am not responsible for any damage caused by you
Damage caused by osintsan.
