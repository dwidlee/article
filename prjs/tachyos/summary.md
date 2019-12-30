## TachyOS

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/bc5b451d38624e44a58c8fd4913bc4a5)](https://www.codacy.com/app/innocentevil0914/TachyOS?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=fritzprix/TachyOS&amp;utm_campaign=Badge_Grade) [![Build Status](https://travis-ci.org/fritzprix/TachyOS.svg?branch=master)](https://travis-ci.org/fritzprix/TachyOS)

> TachyOS is the RTOS based on microkernel architecture portable to constrained hardware.

### Features

+ Support multi-threading
  + The number of threads is limited only by available memory
  + Context-switch overhead is less than 5us in ARM CM4 (STM)
+ Preemptive scheduler with 6 execution priorities  
+ Various lightweight synchronization 
  + Monitor (mutex / condition variable)
  + Event (blocking pub / sub)  
  + Semaphore  
  + Barrier
+ Various Inter-thread communication 
  + Message Queue  
  + Mail Queue  
+ HAL (as static module) [UART / I2C / SPI / TIMER / RTC / GPIO]  

### License

> LGPL V3.0