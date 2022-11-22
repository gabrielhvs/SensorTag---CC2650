![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
# SensorTag - CC2650

<p align="center"><img src="https://www.ti.com/content/dam/ticom/images/products/ic/processors/evm-boards/cc2650stk-top.png:small"/></p>

[**User Guide - CC2650STK SimpleLink™ Bluetooth low energy**](https://usermanual.wiki/Document/CC265020SensorTag20Users20Guide2020Texas20Instruments20Wiki.2070227354.pdf)

The Sensor Tag is a set of sensor, it have a bluetooh conection with a especific Texas Instruments program. This repository provide instructions and software examples for running the CC2650STK with Desktop Computer or another devices with a bluetooh conetion.

Code examples include python codes, interface with ROS and filters implementations. The main implementation was about IMU sensors, Gyroscopic, Accelerometer and Magnetometer.

The [**Datasheet**](https://invensense.tdk.com/wp-content/uploads/2015/02/PS-MPU-9250A-01-v1.1.pdf) is a detailed specification of IMU used. 

### Contents

#### Codes

- **[Simple_Conection](#src)**<br>
- **[Ros_Implementation](#graph-web-server)**<br>
- **[Calibration_Hard_Iron](#ifttt-example)**<br>
- **[Filter_Implementation](#ifttt-example)**<br>


## 💻 Before installing 

Before starting, looking if you have the following requirements:
<!---Estes são apenas requisitos de exemplo. Adicionar, duplicar ou remover conforme necessário--->
* You installed the version more recent of `Visual Studio v1.65.0` 
* * You installed the version more recent of `bluepy python module`

## 🚀 Installing Exploratory-Robot

To install you shold follow the steps:

Linux, macOS e Windows:
```
git clone https://github.com/gabrielhvs/SensorTag---CC2650.git
```
