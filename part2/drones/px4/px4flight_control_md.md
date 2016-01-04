# Flight control algorithm

####PX4源代码
PX4项目建立在这些主要软件模块:

- PX4 Flight Stack (estimation and control, cross-platform)
- PX4 Middleware (IPC / ORB, *nix (NuttX, Linux, MacOS, etc))
- PX4 ESC Firmware (for motor controllers)
- PX4 Bootloader (for STM32 boards)
- Operating System (NuttX or Linux/Mac OS)

项目地址：

- [PX4 Firmware source](http://github.com/PX4/Firmware)

#####**PX4飞行栈**

PX4飞行栈能控制多轴飞行器，航模，直升机，实验飞机和地面车辆的飞行。它由一组单独的应用程序/节点组成。

- [flight control modules](http://github.com/PX4/Firmware/tree/master/src/modules)

#####**PX4中间件**

PX4中间件提供了硬件接口和进程间通信。

- [drivers](http://github.com/PX4/Firmware/tree/master/src/drivers)
- [uORB](http://github.com/PX4/Firmware/tree/master/src/modules/uORB)

#####**PX4电调固件**

PX4电调固件控制无刷电机，可以通过UAV CAN进行交互。

<!--more-->
- [PX4 ESC source](http://github.com/PX4/px4esc)

#####**PX4 Bootloader**

PX4引导装载程序是用于STM32微控制器新飞行软件加载到闪存。用于Pixhawk。

- [PX4 Bootloader source](http://github.com/PX4/Bootloader)

#####**操作系统**

PX4飞行栈和中间件可以在微控制器Nuttx小型操作系统上执行，或者在全面POSIX系统，如Linux，Mac OS 或 BSD。

- [NuttX OS](http://github.com/PX4/NuttX)

<hr>
参考文件：[PX4 Source Code](https://pixhawk.org/firmware/source_code)