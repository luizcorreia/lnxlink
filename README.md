# lnxlink
It's a Linux service for integrating your system with an external application like Home Assistant using MQTT.
LNX Link is inspired by [IOT Link](https://iotlink.gitlab.io/).

# Features
 - **System control** Shutdown, Media, Notifications.
 - **System monitor** CPU, Ram, Network, Media.
 - **Easily expanded** Any new module is automatically imported as long as it meets the required format.

# Installation
```shell
git clone https://github.com/bkbilly/lnxlink.git
cd lnxlink/
pip install -r requirements.txt
python3 run.py
```