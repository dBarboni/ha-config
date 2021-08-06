# NOTE: this is no longer maintained as I have implemented another backup solution

# ha-config
Backup for my Home Assistant configuration

## Requirements
### API keys, credentials, etc.
A file named `secrets.yaml` must be created in the .homeassistant directory with the following contents:

```
# Home Assistant API
## Password for API usage
http_password:

# Location info
## Home
lat_home:
long_home:
time_zone:
address_home:
## Work
lat_work:
long_work:
address_work:

# Devices for device tracker
my_phone_life360:
my_phone_nmap:

# API keys
## Uptime robot
key_uptime:
## OpenWeatherMap
key_owm:

# Waze
waze_include:
waze_exclude:

# IP addresses
## Desktop, must begin with http://...
## Must be running hwinfo and Remote Sensor Monitor
ip_desktop:
## Wemo
ip_wemo:

# MAC addresses
## Xiaomi temp/humidity sensors
mac_sensor_xiaomi_basement:
mac_sensor_xiaomi_bedroom:

# Telegram
telegram_chat_me:
telegram_key:

# MQTT
mqtt_server:
mqtt_port:
mqtt_user:
mqtt_pass:

# Flic buttons
flic_bedroom:

# Home Assistant Community Store (HACS) - Github token
hacs_token:

# Wyze sensors
wyze_motion_hall:

```
### Life360
Configure integration in the Home Assistant frontend.

### Flic service

### Home Assistant Community Store (HACS)
Install according to [these](https://custom-components.github.io/hacs/installation/manual/) instructions.

### ha-wyzesense
Install according to [these](https://github.com/kevinvincent/ha-wyzesense) instructions using the HACS method.
