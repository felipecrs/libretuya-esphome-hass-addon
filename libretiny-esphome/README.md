# ESPHome Home Assistant Add-On

[![ESPHome logo](https://raw.githubusercontent.com/esphome/hassio/main/esphome-dev/logo.png)](https://docs.libretiny.eu/docs/projects/esphome/)

[![GitHub stars](https://img.shields.io/github/stars/kuba2k2/libretiny-esphome.svg?style=social&label=Star&maxAge=2592000)](https://github.com/kuba2k2/libretiny-esphome)
[![GitHub Release][releases-shield]][releases]

## About

This add-on allows you to manage and program your ESP8266, ESP32 and LibreTiny based microcontrollers
directly through Home Assistant **with no programming experience required**. All you need to do
is write YAML configuration files; the rest (over-the-air updates, compiling) is all
handled by LibreTiny ESPHome.

<p align="center">
<img title="LibreTiny ESPHome dashboard screenshot" src="https://raw.githubusercontent.com/esphome/hassio/main/esphome-dev/images/screenshot.png" width="700px"></img>
</p>

[View the LibreTiny ESPHome documentation](https://docs.libretiny.eu/docs/projects/esphome/)

## Example

With LibreTiny ESPHome, you can go from a few lines of YAML straight to a custom-made
firmware. For example, to include a [DHT22][dht22].
temperature and humidity sensor, you just need to include 8 lines of YAML
in your configuration file:

<img title="LibreTiny ESPHome DHT configuration example" src="https://raw.githubusercontent.com/esphome/hassio/main/esphome-dev/images/dht-example.png" width="500px"></img>

Then just click UPLOAD and the sensor will magically appear in Home Assistant:

<img title="LibreTiny ESPHome Home Assistant MQTT discovery" src="https://raw.githubusercontent.com/esphome/hassio/main/esphome-dev/images/temperature-humidity.png" width="600px"></img>

[dht22]: https://esphome.io/components/sensor/dht.html
[releases-shield]: https://img.shields.io/github/v/release/kuba2k2/libretiny-esphome.svg
[releases]: https://github.com/kuba2k2/libretiny-esphome/releases
