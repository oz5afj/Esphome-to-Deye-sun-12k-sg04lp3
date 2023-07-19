# esp32---Deye-sun12k
Esphome component for Deye sun-12k-sg04lp3 to implement into home assistant + Neey 4a Smart Active Balancer

You can use my code as long as you don't try to make money from it.

ESPhome configuration for monitoring and control of Deye inverters in Home Assistant. This include all addresses i could see relevant from the inverter. image
Supported devices

Made specially for Deye 3phase low voltage inverters

    SUN-12K-SG04LP3
  

Hardware diagram

RX / TX between esp and ttl converter way have to be swapped. This seems to be a little different from espboard to espboard. If it dosent communicate(RX/TX led both blinking) Try swap rx/tx on the esp.


esp32 rs485_bb
Home assistant user interfase

