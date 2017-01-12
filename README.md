# Azure IoT Hub Utility

Simple cross platform Python3 utility to manage Azure IoT Devices.

# Platform

Any supporting Python3

# Libraries

Solutions uses requests.

To install

pip3 install requests

# Config File

config.json

Modify with your Azure IoT Hub Connection String

# Commands


Action| Command
------|------
New Device| python(3) iothub.py new deviceId
Delete Device| python(3) iothub.py delete deviceId
List All Devices| python(3) iothub.py List
Device Info| python(3) iothub.py info deviceId
Device Connection String| python(3) iothub.py cs deviceId

