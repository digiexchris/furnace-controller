# d1-mini-furnace-controller
Simple 5 wire furnace controller using the Wemos D1 Mini. Intended for ESPHome and Home Assistant or other automation uses.

## Why this exists
It's difficult to find a power supply to run an esp32 or esp8266 (or any 5vdc device for that matter) off of the 24vac transformer typically used in a furnace. This is intended to provide power and 3 relays connected to an esp8266 so that it can run anywhere that the thermostat wires are run in your house (or, as in my case, mounted directly to the furnace cabinet).
