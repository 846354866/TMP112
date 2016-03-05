[![TMP112](TMP112_I2CS.png)](https://www.controleverything.com/content/Temperature?sku=TMP112_I2CS)
# TMP112
TMP112 Color Light-to-Digital Converter  

The TMP112 device offers high-accuracy digital temperature measurement.
This Device is available from ControlEverything.com [SKU:TMP112_I2CS]

https://www.controleverything.com/content/Temperature?sku=TMP112_I2CS

This Sample code can be used with Raspberry pi.

##Java 
Download and install pi4j library on Raspberry pi. Steps to install pi4j are provided at:

http://pi4j.com/install.html

Download (or git pull) the code in pi.

Compile the java program.
```cpp
$> pi4j TMP112.java
```

Run the java program as.
```cpp
$> pi4j TMP112
```

##Python 
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program

```cpp
$> python TMP112.py
```

The code output is temperature reading in degree celsius and fahrenheit.

