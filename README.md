This repository is a fork of the original Kamerka project.
##########################################################

Seperate from the original code, I'm working on adding more ICS devices and functionalities.

# ꓘamerka 2.0 aka FIST (Flickr, Instagram, Shodan, Twitter)
*Build interactive map of cameras, printers, tweets and photos.* 

The script creates a map of cameras, printers, tweets and photos based on your coordinates. Everything is clearly presented in form of interactive map with icons and popups.

# v5 update 27/11/2019
Added more ICS devices
![](https://i.imgur.com/oHLL1YH.png)

# v4 update
Added RTSP (Real-Time Streaming Protocol)
 ![](https://i.imgur.com/diuLuHd.jpg)
 
 MQTT (Message Queue Telemetry Transport).
![](https://i.imgur.com/LAscLR2.jpg)

Elasticsearch output
![](https://i.imgur.com/ZuHhbf4.jpg)

Additional:
- recursive mode (check each host for open ports and more information)
- "Check ownership" link on map which redirects to bgp.he.net for detailed information about IP
- "Lookup on Shodan" takes you to Shodan details about host

# v3 update
Visualize Industrial Control Systems of any country.  
Use *--country* flag and pass short code for your country.  
To use Street View add your API key in line 109


```
root@kali:~/# python kamerka.py --country PL
```

