---
layout: post
title: Arcturus Robot
description: Initial robot manual mode went through the main computer which delayed commands. Designed and implemented a PCB to switch between manual and autonomous drive mode and interpret CAN commands to manual drive. Also designed a PCB based on the STM32 that interfaces with the Arcturus Robot system for debugging and testing.
skills: 
  - Altium Designer
  - Saturn PCB Toolkit
  - Microcontrollers
  - Soldering

main-image: /STM32New.jpg
---

### **What?**
 - Initial robot manual mode went through the main computer which delayed commands. Designed and implemented a PCB to switch between manual and autonomous drive mode and interpret CAN commands to manual drive
 - Designed and made a PCB based on the STM32 that interfaces with the Arcturus Robot system for debugging and testing.

### **How?**
- Used a Multiplexer and Level Shifter with an STM32 to switch between manual and autonomous. Wrote the firmware using an Arduino library for STM32
- Created schematics for UART, SPI, I2C, GPIO, and power headers


<br>
## **Switch PCB**
{% include image-gallery.html images="Switch.jpg" height="500" %}

<br>
## **Debugger PCB**
{% include image-gallery.html images="debugger.jpg" height="500" %}
