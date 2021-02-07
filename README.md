# f407bootloader

## Steps to flash the bootloader

1. Download and install the STM32 software from [here](https://www.stmicroelectronics.com.cn/content/st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-programmers/stm32cubeprog.html).  
2. Add two jumpers to the fly board as shown below.

![Fly_407zg_Bootloader](https://github.com/FLYmaker/f407bootloader/blob/master/Images/fly_407zg_fix.png)

3. Plug the board in by USB. It should show up in the device manager as shown below.

![Fly_407zg_Bootloader1](https://github.com/FLYmaker/f407bootloader/blob/master/Images/fly_407zg_fix1.png)

4. Open the STM32 software and configure the connection settings as shown below.  

![Fly_407zg_Bootloader2](https://github.com/FLYmaker/f407bootloader/blob/master/Images/fly_407zg_fix2.png)

5. Download the latest copy of the bootloader from [here](https://github.com/FLYmaker/f407bootloader/releases/).  

6. Open the bootloader in the software as shown below.  

![Fly_407zg_Bootloader3](https://github.com/FLYmaker/f407bootloader/blob/master/Images/fly_407zg_fix3.png)

7. Click the "Download" button as shown below.  

![Fly_407zg_Bootloader4](https://github.com/FLYmaker/f407bootloader/blob/master/Images/fly_407zg_fix4.png)

8. Once complete, disconnect the Fly-407ZG from the computer and remove the jumpers. It can now be used as normal.  