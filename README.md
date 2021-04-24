# Tuya_Wechat_Devtools
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.

![智能单插.png](https://github.com/kangkoilxu/Tuya-Wechat-MiniCode/blob/main/panel.jpg)

# 基于涂鸦智能微信小程序SDK开发的智能电量统计WIFI插座
- 支持电压电流电量的查看
- 支持计时功能

## Demo Description

- Equipment distribution network：

  Directly click the button for network distribution: AP network distribution, code scanning network distribution, Bluetooth network distribution and ZigBee network distribution are currently supported

- Experience device functions：

  After adding a device, you can click the device open switch to adjust MQTT message push of the device. It is suggested to use getdevicespeciannotation function in API.JS file to get the instruction set to avoid the possibility of inconsistent names of dp point fields. The content of the push message will be displayed on the page after the instruction is issued normally

- The full version Demo
  Currently support device control, message push, add device (distribution network), home module
