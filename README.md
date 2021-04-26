# OSINT-SAN-Framework

Framework aimed at obtaining data and de-anonymizing users. The tool uses a large number of APIs. Now the tool is being finalized, some functions may not work correctly.

Tool adapted for: Kali Linux * Parrot

PRO Version https://www.youtube.com/watch?v=5oFaQADPtnc


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
  
  
  Dependencies. Alternative text

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
