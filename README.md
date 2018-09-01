# I2C Interface

The library simplifies work with the Arduino Wire library. Talk to the device using methods that only use the device address, registry and/or value.

## Example

To see a real-life usage example, open the [ADXL345](https://github.com/MatthewPatyk/ADXL345-Arduino-I2C-library) usage example, or my other projects that utilize that interface.

```cpp
this->readByte(this->_I2CAddress, ADXL345_REG_ID, deviceID);
this->writeByte(this->_I2CAddress, ADXL345_POWER_CTL, registerValue);
```
