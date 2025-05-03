```
raspi-config

Interfacing Options -> I2C -> Yes
```
```
reboot
```
```
ll /dev/i2c-*
```
```
apt install -y i2c-tools
i2cdetect -l
i2cdetect -y 1
```
