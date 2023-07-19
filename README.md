Esphome - Deye sun-12k-sg04lp3 + Neey 4A
Esphome component for Deye sun-12k-sg04lp3 to implement into home assistant + Neey 4a Smart Active Balancer

You can use my code as long as you don't try to make money from it.

ESPhome configuration for monitoring and control of Deye inverters in Home Assistant. This include all addresses i could see relevant from the inverter. image
Supported devices

Made spe![ha_deye](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/7405110d-552a-48cf-9d87-9ee999f41d8b)
cially for Deye 3phase low voltage inverters

    SUN-12K-SG04LP3
  

Hardware diagram

![esp](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/42f14538-f3c7-43f3-bc50-e924da21e121)

RX / TX between esp and ttl converter way have to be swapped. This seems to be a little different from espboard to espboard. If it dosent communicate(RX/TX led both blinking) Try swap rx/tx on the esp.


esp32 rs485_bb
Home assistant user interfase

![neey](https://github.com/oz5afj/esp32-Deye-sun-12k-sg04lp3/assets/58389425/d6e937b3-cc3c-46cf-86f5-c46d07fd0bc8)
