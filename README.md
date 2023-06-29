# 2023_06_29_MicroPythonUART2PinOnOff
The following code allows to trigger on and off the pin of the target micro python device with UART.

![image](https://github.com/EloiStree/2023_06_29_MicroPythonUART2PinOnOff/assets/20149493/2e6d7b72-a14a-4063-ae92-7224f23013f0)

```
# 0; Set all pin to false 
# 1; Set all pin to true 
# d01; Set pin at index 1 to false
# d15; Set pin at index 5 to True
# d120; Set pin at index 20 to True
# d021; Set pin at index 21 to False
# d041; Will ignore as pin at index 41 is not registered
# ; or \n will end the serial message
# ' ' will split the message in several command
#Example: 0 d12 d120 d04;
```
