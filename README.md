
[![ADC121C_MQ5](ADC121C_I2CGAS_MQ5.png)](https://store.ncd.io/product/mq-5-lpg-lng-natural-gas-iso-butane-propane-gas-sensor-adc121c-12-bit-adc-i2c-mini-module/).

# ADC121C_MQ5
The MQ-5 is capable of sensing LPG Propane, LNG Natural Gas, Iso-butane, and Propane Town Gas air concentration levels between 200 and 10,000ppm. The ideal sensing condition for the MQ5 is 20°C ±2°C at 65% ±5% humidity.
This Device is available from www.ncd.io 

[SKU: ADC121C_MQ5_I2CS]

(https://store.ncd.io/product/mq-5-lpg-lng-natural-gas-iso-butane-propane-gas-sensor-adc121c-12-bit-adc-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface ADC121C_MQ5 Sensor With Raspberry Pi : 

1. <a href="https://store.ncd.io/product/mq-5-lpg-lng-natural-gas-iso-butane-propane-gas-sensor-adc121c-12-bit-adc-i2c-mini-module/">ADC121C_MQ5 LPG,LNG and methane Gas Sensor</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>

3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python

Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1
Download (or git pull) the code in pi. Run the program.

```cpp

$> python ADC121C_MQ5.py

```

The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
