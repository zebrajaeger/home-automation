# Home-automation

My way to home automation.

This is an documentation project only

## My related projects

* [ESP32 LED Dimmer](https://github.com/zebrajaeger/esp32-led-dimmer)

## Server

### Hardware

* Raspberry Pi
* CC2531 USB stick + CC Debugger + Downloader cable

### Software

* Raspbian OS
* Docker
* hass.io (<https://www.home-assistant.io/hassio/>)
  * Nice integration for much of the following components
* zigbee2mqtt (<https://github.com/Koenkk/zigbee2mqtt>)
  * Bridge between Zigbbe hardware and MQTT server
* mosquitto (https://mosquitto.org/)
  * MQTT server
* Node-Red (<https://nodered.org/>)
  * Flow diagram editor (and executor)
* InfluxDB (<https://www.influxdata.com/>)
  * Database for time dependent data
* Grafana (<https://grafana.com/>)
  * Pretty diagrams from data source

## Devices

### Switch

* <https://www.aqara.com/en/smart_wireless_mini_switch.html>
* <https://www.ikea.com/de/de/p/tradfri-fernbedienung-30443124/>

### Sensor

* <https://www.aqara.com/en/temperature_humidity_sensor.html>
* <https://xiaomi-mi.com/sockets-and-sensors/xiaomi-mi-temperature-humidity-sensor/>

### Actor

* <https://www.ikea.com/de/de/p/tradfri-led-leuchtmittel-e14-600-lm-kabellos-dimmbar-weissspektrum-opalweiss-80408585/>

## DIY

### LED-Dimmer

  * <https://github.com/zebrajaeger/esp32-led-dimmer>
