Esphome - Deye sun-12k-sg04lp3 + Neey 4A
Esphome component for Deye sun-12k-sg04lp3 to implement into home assistant + Neey 4a Smart Active Balancer

You can use my code's as long as you don't try to make money from it.

ESPhome configuration for monitoring and control of Deye inverters in Home Assistant. This include all addresses i could see relevant from the inverter. 
![ha_deye](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/4ab7bf48-95e2-4784-bcf9-48e3f7842a30)


## Supported devices

Made specially for Deye 3phase low voltage inverters

    SUN-12K-SG04LP3(confirmed)
    SUN-8K-SG04LP3
    SUN-6K-SG04LP3
    SUN-5K-SG04LP3

 
## Hardware diagram

![bord_485](https://github.com/oz5afj/Esphome-to-Deye-sun-12k-sg04lp3/assets/58389425/81b05cd3-0532-4be6-8087-21d37ce6e0ff)

![bord1_gnd](https://github.com/oz5afj/Esphome-to-Deye-sun-12k-sg04lp3/assets/58389425/bb2155d3-647d-478d-a817-e24acddba704)

If you use an external rs485/ttl print.
Is it important to make a gnd connection between the 2 sides of the rs485/TTL printer, or can voltage differences occur that will burn the print out over time.




## Home assistant user interfase - Neey

![neey](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/d6e937b3-cc3c-46cf-86f5-c46d07fd0bc8)

## Requirements

 
![bord1](https://github.com/oz5afj/Esphome-to-Deye-sun-12k-sg04lp3/assets/58389425/a729788e-e129-43d7-89c4-076b212cdd4e)

![antenne](https://github.com/oz5afj/Esphome-to-Deye-sun-12k-sg04lp3/assets/58389425/c2390540-8592-4363-89f5-75c9505d1656)


    ESP32 - S3   (Must be used if you want to run Deye + Neey on the same esp32)
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



#  I developed Deye/esp32 code in Nov 2022

And shortly afterwards I shared it on Facebook in with some "friends."
It was not my intention to share my code on github, but I can see several others trying to profile my idea and code.
I dreamed that others would take my code and refine it and maybe improve it so that it could be perfect and still be free for everyone without someone having to pay the money for it.
The deye /eps32 code, the neey code comes from: https://github.com/syssi/esphome-jk-bms)https://github.com/syssi/esphome-jk-bms
