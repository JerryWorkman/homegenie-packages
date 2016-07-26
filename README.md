# homegenie-packages
Homegenie packages that I have created

Homegenie (http://www.homegenie.it/) is a IoT controller built with C-Sharp / mono. It runs on many operating systems including Windows and Linux - including Raspberry Pi

These files are in Homegenie package format and can be added to your Homegenie system. They can also be viewed with any text editor. All are in C# unless otherwise indicated.

## 1000-PcmWiFi_Energy_Monitor.hgx

Reads energy use (watts and Kwh) from a PcmWiFi system. I don't know if it's commercially available anymore. My system failed a few months ago. I replaced it with OpenEnergyMonitor hardware.
  
## 1004-PCMWIFI_Page_Scraper.hgx

Uses page scraping to retrieve PCMWIFI values from the device web page.
  
## 1005-Python_HTML_Scraping.hgx

Used Python Beautiful Soup (https://www.crummy.com/software/BeautifulSoup/) to scrape values from a web page. Not suitable for Rasberry Pi because of memory requirements.

## 1006-WiFi_Thermostat.hgx

Radio Thermostat interface

## 1007-WIFI_Thermostat_Python.hgx

Radio Thermostat interface in Python

## 1008-RFXCOM_Sensors.hgx

Reads values from RFXCOM sensors (Oregon Scientific Therm/Humidity)
  
