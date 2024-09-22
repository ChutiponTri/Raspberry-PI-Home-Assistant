# Raspberry-PI-Home-Assistant
To Check Network Connection Status
```ini
ha network info
```
To Setup Auto WiFi Connection for Raspberry PI Home Assistant OS Run This Following Line in HA Terminal
```ini
ha network update wlan0 --ipv4-method auto --wifi-mode infrastructure --wifi-auth wpa-psk --wifi-ssid "MY-SSID" --wifi-psk "MY_PASS"
```
To Scan Available WiFi Connections
```ini
ha network scan wlan0
```
To Manually Connect to WiFi Connection
```ini
ha network set wlan0 --ipv4-method auto --wifi-mode infrastructure --wifi-auth wpa-psk --wifi-ssid "MY-SSID" --wifi-psk "MY_PASS"
```
