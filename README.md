# Sonoff
Sonoff NSPanel Esphome
# NSPanel Custom with HA Blueprint Modded to work with US ver
This version of HA Blueprint has 

- Option for time format 12/24 hrs which can be selected from Automations
- Shows WiFi Signal 


# How To Use.
just create a new device and replace the code with the code below and make the changes where mentioned # CHANGE ME 


```


###### copy and paste from here begin ######

substitutions:

###### CHANGE ME START ######

  device_name: "YOUR NSPANEL_NAME"  # Nspanel Deivce Name Must be in lowercase and no speacial chars #CHANGE ME
  wifi_ssid: "YOUR WIFI SSID"  # CHANGE ME 
  wifi_password: "YOUR WIFI PASSWORD"  # CHANGE ME 
  nextion_update_url: "http://homeassistant.local:8123/local/nspanel_us.tft" # CHANGE ME , Change the home assistant url ! IMP 

##### CHANGE ME END #####



##### DO NOT CHANGE ANYTHING! #####

packages:
  ##### download esphome code from Github
  remote_package:
    url: https://github.com/abidullah/Sonoff
    ref: main
    files: [nspanel.yaml]
    refresh: 300s

##### DO NOT CHANGE ANYTHING! #####

###### copy and paste from here end ######
```



Thanks to:


Blackymas:  https://github.com/Blackymas/NSPanel_HA_Blueprint for the original code

SmartHome Yourself: https://www.youtube.com/c/SmarthomeyourselfDe_DIY

Masto: https://github.com/masto/NSPanel-Demo-Files

Marcfager: https://github.com/marcfager/nspanel-mf

lovejoy77: https://github.com/lovejoy777/NSpanel

Hellis81: https://github.com/Hellis81/NS-panel
