#Simple Bluetooth  

A cheap and easy way to add Bluetooth to an AWQUA device is to drop in an HC-06 module, which we call `simple-bluetooth`.  

![HC-06 module](https://github.com/AWQUA/Communication/blob/master/Bluetooth/simple-bluetooth/images/hc-06.jpg)  

These preassembled modules can be found all over the web for under $10. Connect one to your AWQUA device using the exposed hardware serial connection that can also be used to reprogram the device. It's a breeze to send data from your AWQUA device to an Android device with this module. (It's possible, but apparently quite tricky, to share data with an iPhone using this module; a Bluetooth Low Engery (BLE) module is a better choice for Apple products.)  

Here's an example diagram showing you how to connect the HC-06 `simple-bluetooth` module to the `basic-handheld-turbidimeter`:  

![connecting simple-bluetooth](https://github.com/AWQUA/Communication/blob/master/Bluetooth/simple-bluetooth/images/bluetooth-handheld-turbidimeter.png)

All AWQUA devices are fully open-source, and have circuit boards detailed in EagleCAD. To find a device's hardware serial interface, check the board (.brd) file in the device's subdirectory in the Measurement repo. For example, the directory for the `basic-handheld-turbidimeter` in the image above is [here](https://github.com/AWQUA/Measurement/tree/master/turbidity/devices/basic-handheld-turbidimeter/).
