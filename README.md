# Azure IoT Hub Utility

Simple cross platform Python3 utility to manage Azure IoT Devices.

# Platform

Any supporting Python3

# Libraries

Solutions uses requests.

To install

pip3 install requests

# Config File



See [Setting up Azure IoT Hub](http://thinglabs.io/workshop/cs/nightlight/setup-azure-iot-hub/)
for information of where to obtain the connection string from.

Edit the config.json and replace the connection string with your Azure IoT Hub Connection String.

# Commands



Action| Command
------|------
New Device| python(3) manage.py new deviceId
Delete Device| python(3) manage.py delete deviceId
List All Devices| python(3) manage.py List
Device Info| python(3) manage.py info deviceId
Device Connection String| python(3) manage.py cs deviceId

