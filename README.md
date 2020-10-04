# wpa_supplicant-example
sample wpa_supplicant.conf  


```
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev  
update_config=1  
country=AU  

network={  
    scan_ssid=1  
    ssid="NETWORK-NAME"  
    psk="NETWORK-PASSWORD"  
    key_mgmt=WPA-PSK  
}
