Esphome - Deye sun-12k-sg04lp3 + Neey 4A
Esphome component for Deye sun-12k-sg04lp3 to implement into home assistant + Neey 4a Smart Active Balancer

You can use my code as long as you don't try to make money from it.

ESPhome configuration for monitoring and control of Deye inverters in Home Assistant. This include all addresses i could see relevant from the inverter. 
![ha_deye](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/4ab7bf48-95e2-4784-bcf9-48e3f7842a30)


## Supported devices

Made specially for Deye 3phase low voltage inverters

    SUN-12K-SG04LP3(confirmed)
    SUN-8K-SG04LP3
    SUN-6K-SG04LP3
    SUN-5K-SG04LP3

 
## Hardware diagram

![esp](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/42f14538-f3c7-43f3-bc50-e924da21e121)

RX / TX between esp and ttl converter way have to be swapped. This seems to be a little different from espboard to espboard. If it dosent communicate(RX/TX led both blinking) Try swap rx/tx on the esp.

Several have powered the esp32 from CN2 pin 7&8 with 12V into a USB converter. (BE AWARE THAT IF YOU POWER OFF THE INVERTER REMOTELY, YOU CANT POWER IT UP AGAIN REMOTELY AS THE POWER TO THE ESP IS GONE)


Home assistant user interfase - Neey

![neey](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/d6e937b3-cc3c-46cf-86f5-c46d07fd0bc8)

## Requirements

    ESP32 - S3 
![esp S3](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/4f16a8ef-934a-47f1-a69e-8dd488eb31bb)

    TTL To RS485 Module with automatic flow control
![ttl](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/0d96496b-acad-4d77-bfc7-8fad2df71968)

## Installation

    Create your esp32 in esphome in home assistant
    Upload the your basis config via. usb from pc.
    Test wireless upload
    Copy all content (make sure you have your wifi ssid&password in the secrets)
    Edit the sensors in the config if you like
    Upload wireless

