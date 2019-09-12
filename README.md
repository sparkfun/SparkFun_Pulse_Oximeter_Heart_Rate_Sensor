SparkFun Pulse Oximeter and Heart Rate Monitor 
========================================

![SparkFun Pulse Oximeter and Heart Rate Monitor](https://cdn.sparkfun.com/assets/parts/1/3/6/6/4/15219-SparkFun_Pulse_Oximeter_and_Heart_Rate_Sensor_-_MAX30101__Qwiic_-01.jpg)

[*SparkFun Pulse Oximeter and Heart Rate Monitor (SEN-15291)*](https://www.sparkfun.com/products/15219)

The SparkFun Pulse Oximeter and Heart-Rate Sensor is an I&sup2;C based [biometric](https://en.wikipedia.org/wiki/Biometrics) sensor, utilizing two chips from Maxim Integrated: 
the MAX32664 Bio Metric Sensor Hub and the MAX30101 Pulse Oximetry and Heart-Rate Module.

The MAX30101 does all the sensing by utilizing its' internal LEDs to bounce light off the arteries and arterioles in your finger's subcutaneous layer and sensing how much light 
is absorbed with its' photodetectors . This is known as [photoplethysmography](https://en.wikipedia.org/wiki/Photoplethysmogram). This data is passed onto and analyzed by the 
MAX32664 which applies its' algorithms to determine heart rate and blood oxygen saturation (SpO2). The embedded algorithm uses digital filtering, pressure/position compensation, 
advanced R-wave detection and automatic gain control to determine the heart rate in beats per minute while minimizing power.  SpO2 results are reported as percentage of hemoglobin 
that is saturated with oxygen. It also provides useful information such as the sensor's confidence in its' reportings as well as a handy finger detection data point. To get the 
most out of the sensor we've written an Arduino Library to make it easy to adjust all the possible configurations.

Repository Contents
-------------------

* **/Documentation** - Data sheets and additional product information.
* **/Firmware** - Programming File for the MAX32664 
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Arduino Library](https://github.com/sparkfun/SparkFun_Bio_Sensor_Hub_Library)** - Arduino Library with Example Sketches
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-pulse-oximeter-and-heart-rate-monitor-hookup-guide)** - Basic hookup guide for the SparkFun Pulse Oximeter and Heart Rate Sensor.

Product Versions
----------------
* [SEN-15291](https://www.sparkfun.com/products/15219)- SparkFun Version 1.0

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_

