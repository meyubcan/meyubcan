## Hi, I'm Eyüb

I'm an embedded systems engineer and the founder of [TECH-OHM](https://tech-ohm.com), an embedded systems design company in Ankara. We build the hardware and software that run inside products: custom boards, firmware, power electronics, and the SaaS platforms, dashboards and AI technologies that connect them. We also teach embedded systems.

Our aim is to take an idea from the first schematic to series production, with hardware and software designed by the same team. That way problems get caught on the bench instead of in the field.

### What I work on

- Embedded hardware and firmware on STM32, ESP32, Nordic and ATtiny, with FreeRTOS, custom bootloaders and OTA updates
- Industrial communication: CAN, Modbus over RS-485, Ethernet, LoRa, BLE
- Power electronics and battery management: SMPS, DC-DC converters, BLDC and stepper drivers
- IoT, dashboards and edge AI for connected devices
- PCB design, 2 to 4+ layers, with EMC in mind

We work for defense, healthcare, agriculture, automotive and industry. I'm also a co-founder of Bolpet Plast Recycling, where I designed the machines and automation for a PET bottle recycling plant.

### Projects here

Everything below comes from work done at [TECH-OHM](https://tech-ohm.com). Each repository has a block diagram, a pin table and notes on how it works.

**Power and motor control**
- [stm32-4s-bms-home-automation](https://github.com/meyubcan/stm32-4s-bms-home-automation): 4S Li-ion monitoring, passive balancing, thermal protection and Bluetooth-controlled outputs on STM32F407.
- [stm32-bldc-six-step-driver](https://github.com/meyubcan/stm32-bldc-six-step-driver): six-step commutation for a hall-sensored BLDC motor on STM32F103.
- [stm32-tmc2209-uart](https://github.com/meyubcan/stm32-tmc2209-uart): configuring a TMC2209 stepper driver and reading its status over single-wire UART.
- [stm32-input-capture-speed](https://github.com/meyubcan/stm32-input-capture-speed): frequency and RPM measurement with timer input capture.

**Real-time and communication**
- [stm32-freertos-smart-home](https://github.com/meyubcan/stm32-freertos-smart-home): a multitasking control application with FreeRTOS. Queues, mutexes and interrupt-to-task handoff in one project.
- [stm32-nextion-hmi-uart](https://github.com/meyubcan/stm32-nextion-hmi-uart): UART framing and command parsing between a Nextion touch display and STM32.
- [stm32-sim800l-sms-alarm](https://github.com/meyubcan/stm32-sim800l-sms-alarm): SMS alert over SIM800L when an analog value crosses a threshold.
- [stm32-dht11-bluetooth](https://github.com/meyubcan/stm32-dht11-bluetooth): reading a DHT11 without a library and sending the data to a phone over HC-05.
- [stm32-bluetooth-morse-lcd](https://github.com/meyubcan/stm32-bluetooth-morse-lcd): decoding Morse sent over Bluetooth and printing it on a character LCD.

**Other**
- [stm32f0-tinyml-morse](https://github.com/meyubcan/stm32f0-tinyml-morse): a small neural network on a Cortex-M0 that decodes Morse from button presses, built with X-CUBE-AI.
- [stm32f0-elevator-keypad](https://github.com/meyubcan/stm32f0-elevator-keypad): elevator call logic as a state machine with a 4x4 keypad.
- [stm32f0-timer-uart-dac-adc](https://github.com/meyubcan/stm32f0-timer-uart-dac-adc): timers, UART, DAC and ADC driven entirely by interrupts.
- [stm32-dot-matrix-printhead](https://github.com/meyubcan/stm32-dot-matrix-printhead): driving a 9-pin dot matrix print head directly from STM32.
- [stm32-proteus-lm35-lcd](https://github.com/meyubcan/stm32-proteus-lm35-lcd): STM32 simulation in Proteus, with the steps to load firmware built in CubeIDE.

Every README is in English with a Turkish version next to it. Schematics and board photos are being added, starting with the BMS board.

### Contact

[tech-ohm.com](https://tech-ohm.com) · [LinkedIn](https://www.linkedin.com/in/m-ey%C3%BCb-can-3a3883199/) · info@tech-ohm.com
