<p align="center">
    <img src="https://rawgit.com/samnium/IoTWork/master/images/IoTWorl.Logo.png">
</p>

# IoTWork

IoTWork is an home made framework for small devices (and their sensors).
You can use it in to build a IoT Network or simply a Sensors Network

IoTWork project includes three main components:

* [IoTWork.Reader](https://github.com/samnium/IoTWork.Reader): c# application to run on a IoT Device
* [IoTWork.Bridge](https://github.com/samnium/IoTWork.NetBridge): a C library and C# bridge to allow a IoTWok.Reader to access to the hardware on a Linux platform
* IoTWork.Central: c# server side applications

Current version of IoTWork.Reader focuses on the [Raspberry Pi3](https://www.raspberrypi.org/) and [Sense Hat](https://www.raspberrypi.org/products/sense-hat/); the operating system is the [raspbian](https://www.raspbian.org/) Linux and the toolchain used is [mono](http://www.mono-project.com/).

## The IoTWork.Network

![IoTWork.Network](https://github.com/samnium/IoTWork/blob/master/images/IoTWork.Network.Diagram.png)
