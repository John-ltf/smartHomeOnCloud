# Smart Home On Cloud

A set of tools, code, applications and CI/CD mechanisms to leverage IoT home devices via Azure Cloud.

The repo consists of two parts, one for the installation of processes/devices on home infrastructure and the other one for the provisioning of resources on Azure Cloud.
On The home side, there are also implemented a local mqtt broker and a python proccess that replicates the messages from local MQTT to Azure IoT Hub.

The repo currently supports the Xiaomi Mijia LYWSD03MMC thermometer and Xiaomi Mi Scale V2 (MIBFS) devices. However it is easy to extend it and add more devices and controls.
