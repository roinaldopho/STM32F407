Data sheet STM32F407 Discovery Kit

The STM32F4DISCOVERY offers the following features: 
•STM32F407VGT6 microcontroller featuring 32-bit ARM Cortex®-M4 with FPU core, 1-Mbyte Flash memory, 192-Kbyte RAM in an LQFP100 package
•On-board ST-LINK/V2 on STM32F4DISCOVERY or ST-LINK/V2-A on STM32F407G-DISC1
•ARM®mbedEnabled™
•USB ST-LINK with re-enumeration capability and three different interfaces:–
Virtual COM port (with ST-LINK/V2-A only)–Mass storage (with ST-LINK/V2-A only)–Debug port
•Board power supply: –Through USB bus–External power sources:3 V and 5 V
•LIS302DL or LIS3DSH ST MEMS 3-axis accelerometer
•MP45DT02 ST MEMS audio sensor omni-directional digital microphone
•CS43L22 audio DAC with integrated class D speaker driver
•Eight LEDs:
–   LD1 (red/green) for USB communication
–   LD2 (red) for 3.3 V power on
–   Four user LEDs, LD3 (orange), LD4 (green), LD5 (red) and LD6 (blue)
–   2 USB OTG LEDs LD7 (green) VBUS and LD8 (red) over-current
•Two push buttons (user and reset)
•USB OTG FS with micro-AB connector
•Extension header for all LQFP100 I/Os for quick connection to prototyping board and easy probing
•Comprehensive free software including a variety of examples, part of the STM32CubeF4 package or STSW-STM32068 for legacy standard library usage

Reference Manual 

Program bawaan dari STM32F407 DIscovery Kit merrupkan program untuk menjalankan board seperti mouse
Caranya:
1. Pastikan JP1 dan CN3 terkoneksi
2. Hubungkan board dengan power supply dengan menhubungkan kabel mini B ke port CN1
3. Pastikan 4 buah LED akan menyala
4. Hubungkan satu lagi kabel micro-usb ke port CN5 
5. Tekan tombol User
6. Selesai, STM32F407 DIscovery Kit telah menjadi sebuah mouse :)

Progress:
Telah menginstall GNU ARM Esclipe
Telah menginstall Esclipse Oxygen
Telah menginstall GNU Tool ARM Embedded
Telah menginstall ST-LINK 07
Telah mencoba program bawaan STM32F407 yang berfungsi sebagai mouse

Progress tgl 6 November 2017:
![error saat run](https://user-images.githubusercontent.com/32188146/32440077-2d9634e6-c324-11e7-9bfb-7e7cb8a7cc20.png)

