# jetsonTX1GPIO
A straightforward library to interface with the NVIDIA Jetson TX1 Development Kit GPIO  pins.

Based on Software by RidgeRun
https://developer.ridgerun.com/wiki/index.php/Gpio-int-test.c
 * Copyright (c) 2011, RidgeRun
 * All rights reserved.

and ideas from Derek Malloy Copyright (c) 2012
https://github.com/derekmolloy/beaglebone

exampleGPIApp.cpp describes a simple usage case using a tactile button and LED as input and output.
这个项目中主要是jetsonGPIO.c提供了在Linux系统下sysfs方式控制GPIO的接口配置函数，只需要知道sysfs GPIO编号就能
配置板上的相应的GPIO口。
