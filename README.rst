MPU-6050 Python

This program handles the I2C communication between an Onion Omega and a MPU-6050 Gyroscope/Accelerometer sensor.

For this to work you will need the Omega I2C libraries and python installed:

``opkg update && opkg install python-light pyOnionI2C``

This is a very slight modification to the Raspberry Pi MPU-6050 code by Martijn Tijndagamer, which is available on [GitHub](https://github.com/Tijndagamer/mpu6050)

Please note that I have modified only the MPU-6050 Python module itself, not any of the packaging or metadata, so this will not correctly build for install with pip.
