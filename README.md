esp32cam pin for sensor sda,scl 15,14 echo,trig 12,13 (do not pinmode input pin13)

#ISSUE 1

A serial exception error occurred: Cannot configure port, something went wrong. Original message: PermissionError(13, 'A device attached to the system is not functioning.', None, 31)
Note: This error originates from pySerial. It is likely not a problem with esptool, but with the hardware connection or drivers.

https://stackoverflow.com/questions/76146837/a-fatal-esptool-py-error-occurred-cannot-configure-port-permissionerror13-a

#ISSUE 2

Brownout detector was triggered

https://www.modulemore.com/en/article/51/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%9B%E0%B8%B4%E0%B8%94-error-brownout-detector-was-triggered-%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%97%E0%B8%B3%E0%B9%83%E0%B8%AB%E0%B9%89-esp32-%E0%B8%A7%E0%B8%99%E0%B8%A5%E0%B8%B9%E0%B8%9B%E0%B8%99%E0%B8%A3%E0%B8%81%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B8%AB%E0%B8%A2%E0%B8%B8%E0%B8%94?srsltid=AfmBOorR_hLhX5M_uze7bSm8ANJw_xF52CJvXiN33IynCIv0gKFJopQf
