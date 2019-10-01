[![Contributors][contributors-shield]][https://github.com/emanuel36/sensor-node-LoRa/graphs/contributors]
[![Stargazers][stars-shield]][https://github.com/emanuel36/sensor-node-LoRa/stargazers]
[![Issues][issues-shield]][https://github.com/emanuel36/sensor-node-LoRa/issues]
[![LinkedIn][linkedin-shield]][https://www.linkedin.com/in/emanuel36/]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</p>


## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Detailed description](#detailed-description)
  * [Components Specifications](#components-specifications)
  * [Schematic](#schematic)
  * [Board](#board) 
* [Assembled Board With Components](#assembled-board-with-components)
* [Contact](#contact)


## About The Project

This is a project of a new LoRa device sensor-node. This device is capable of collecting environment data such as temperature, humidity, soil moisture and ambient as well as sending all data to a LoRaWAN gateway from miles away. The most impressive feature is the extremely low current draw of this device, because each component was analyzed and the low power consumption was one of the most analyzed aspects in the selection process. The electrical and power system is designed for decades of operation, with a combination of a large rechargeable battery and a solar-powered recharge system. In addition to collecting data about the environment, the device can signal its current status through an LED. It is also capable of detecting sensors reading errors and the battery level. This device is designed to work automatically without any human intervention. As can be seen from the [component specifications](#components-specifications) table, this device is very inexpensive, therefore it is suitable equipment to apply to a wireless sensor network in an agricultural field.

### Built With
* [LoRaWAN](https://lora-alliance.org/)
* [PIC16F18426](https://www.microchip.com/wwwproducts/en/PIC16F18426)
* [MPLAP X IDE](https://www.microchip.com/mplab/mplab-x-ide)


## Detailed Description


### Components specifications

| Component   | Description/Documentation   | Price (USD)   |
|---------------------------------  |:-----------------------------------------------------------------------------------------------------------------------------------------:  |------------:  |
| Microcontroller   | [PIC16F18426](https://www.microchip.com/wwwproducts/en/PIC16F18426)   | $1,02   |
| LoRa Transmiter   | [SX1276](https://www.semtech.com/products/wireless-rf/lora-transceivers/sx1276)   | $4,15   |
| Solar Panel   | Wavgat solar panel 1W/5V  | $1,31   |
| Voltage regulator   | [LM2596](http://www.ti.com/product/LM2596)  | $0,30   |
| Battery   | [Panasonic NCR18650B](https://www.batteryspace.com/prod-specs/NCR18650B.pdf)  | $4,75   |
| Battery Holder  | [BK-18650-PC2](http://www.memoryprotectiondevices.com/datasheets/BK-18650-PC2-datasheet.pdf)  | $0,49   |
| Light Sensor  | [MAX44009](https://www.maximintegrated.com/en/products/interface/sensor-interface/MAX44009.html)  | $1,55   |
| Air Temperature/Humidity Sensor   | [Sensirion SHT30](https://www.sensirion.com/en/environmental-sensors/humidity-sensors/digital-humidity-sensors-for-various-applications/)   | $1,90   |
| Soil Moisture Sensor  | Capacitive soil moisture sensor v1.2  | $0,76   |
| Soil Temperature  | [DS18B20](https://www.maximintegrated.com/en/products/DS18B20)  | $1,00   |


### Schematic

### Board

## Assembled Board With Components

## Contact

Emanuel Angelim - [Linkedin](https://www.linkedin.com/in/emanuel36/) - emanuel.tiec@gmail.com

Project Link: [https://github.com/emanuel36/sensor-node-LoRa](https://github.com/emanuel36/sensor-node-LoRa)
