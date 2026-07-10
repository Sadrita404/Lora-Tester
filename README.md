






|Title | Lora Tester |
|:-- |:--|
|Author | Sadrita Neogi|



## Overview
It is an open source Lora Tester it works as programming tool for any electronic components , and we can put that in the breadboard whrere the breadboards parallel pins are internally connected to the M5 stack adv and the gpio pin so that we can programme any electronic components independently, don't need to connect any wires . Also we can programme EEPROM chips also it has an custom pcb for eeprom Reader and writer through which we can program that also . It is aslo portable and contails additional USB port and 160 gpio pins as output.Also the breadboard is fully custom since each of the header pins of breadboard is programmable to which components we put in.

## Why I chose this project?

So behind choosing this project is actually whenever I need to program any electronic components, I found it hard every time I need to open the laptop installing the libraries and I want something dedicated to only programming this chips and this electronic components, so for that I have come up with this design where it is an portable device in which we can program test and see the results of each electronic components individually without connecting with wire we can directly program it using the breadboard since the breadboard is internally connected with the GPIO pins



##  How to use this project
We can use this project for many purpose, but the main purpose would be programming and testing out electronic components with a wide range of variety at once at one place where we can program it and check whether it is fit. Also, we don't need to connect any wire for it.


## Features

* We can programme any electronic component
* Has 160 GPIO pin (output)
* Has custom breadboard
* Test run electronic components
* See plot graph in the display for various component
* Has custom EEPROM Reader and writer
* Has additional USB ports
* Custom 3d printed enclosure
* Fully Open Source

<img width="784" height="569" alt="Screenshot 2026-07-10 at 9 29 38 AM" src="https://github.com/user-attachments/assets/9d44f285-a043-43a2-997f-24f0a58ceaab" />


## Software 

For software I will use linux for this build and it is also open source 

**[https://www.raspberrypi.com/software/](https://www.raspberrypi.com/software/)**

### Linux 

**[https://github.com/raspberrypi/linux](https://github.com/raspberrypi/linux)**

### The Linux kernel Documentation - [DOC Link ](https://www.raspberrypi.com/documentation/computers/linux_kernel.html)

In the raspberrypi [website](https://www.raspberrypi.com/documentation/computers/linux_kernel.html) the documentation about downloading and use cases of Linux for raspberrypi is well documented and everything is written there, so please go check it out and read through the documentation. It is well documented and everything is listed there.


|  |  |  | Building Process |  |  |
| :-: | :-: | :-: | :-: | :-: | :-: |
| <img src="https://github.com/user-attachments/assets/5f421bf3-8f95-43d0-9821-bcfc466319c5" width="250" alt="4" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/f228881d-51fc-426b-bcae-2975739d9fcf" width="250" alt="6" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/6ca4f06c-ad86-423b-9ce8-e0f24289eb29" width="250" alt="9" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/690430fc-f736-4186-84b8-66568f8e5f88" width="250" alt="16" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/9f33662d-2197-4d7a-a5c5-ef6e5d86b9b4" width="250" alt="19" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/2946c2a4-a198-406e-805b-bd45cfbd4cc4" width="250" alt="22" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/125aaded-4ad3-4f3c-b6dc-133094b93619" width="250" alt="23" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/7c931041-b525-4d6c-9ac7-b48a05d7f141" width="250" alt="29" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/07a1fb6c-9603-4b08-a1a0-afe28a35ccfd" width="250" alt="30" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/f96189e5-6d3d-41d8-9699-5944aae21477" width="250" alt="33" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/9895eb2a-069f-46e2-9b0b-8f08aebf33d1" width="250" alt="38" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/f395eee7-369e-4a30-80d6-81c50e94ef1f" width="250" alt="42" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/775753af-10b9-422e-bad9-b1445ddd4e5a" width="250" alt="43" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/224e3e70-70d3-47e9-9b8c-85caf4ab5a8c" width="250" alt="44" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/40850be6-349c-4933-ad11-550b025aafc9" width="250" alt="45" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/a2faa7b1-bf00-43f2-8a4d-ef53b9e1e95c" width="250" alt="47" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/828a7634-2732-442c-b2fb-a28535f7f84e" width="250" alt="51" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/5d9b30f9-5e22-4dfc-bf80-de109b4d6434" width="250" alt="52" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/cce72017-326a-42bb-afa2-bf1bc56b7e0a" width="250" alt="55" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/0f3cb083-f157-46b6-b6eb-3397fac408f7" width="250" alt="56" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/05cc87c3-b6f5-4979-81ef-96f25d874d9f" width="250" alt="58" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/98a8a95f-6b3e-48f6-9c8c-230186d7875a" width="250" alt="59" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/addd36fe-853a-408c-9de6-26e7edcd70ed" width="250" alt="60" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/704cb764-2d78-42d0-83e0-acde705d89ed" width="250" alt="61" style="border-radius: 12px;" /> |















| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
| --- | --- | --- | --- | --- | --- |
| PCB(moq5) | The EEPROM Writer and Reader | 5 | 4 | [Link](https://jlcpcb.com/) | JLCPCB |
| Raspberry pi zero 2 w | For display and EEPROM | 1 | 19.8 | [Link](https://makerbazar.in/products/raspberry-pi-zero-development-board?variant=49481181757680&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&gad_source=1&gad_campaignid=17426677322&gbraid=0AAAAACLxaAZAdAlrgsOcs3GQwu9U7FzfL&gclid=Cj0KCQjwjb3SBhDgARIsAMKiWzjPPwkDZNPhgg7d7frjodxCyeMHUu6z9B3xtBH47Y2n-kVbVg5weskaAkvXEALw_wcB) | Makerbazer |
| M5Stack Cardputer Adv | Main Board for for programming | 1 | 29.90 | [Link](https://shop.m5stack.com/products/m5stack-cardputer-adv-version-esp32-s3) | m5stack |
| Breadboard | For the components to Put in | 1 | 0.4 | [Link](https://robu.in/product/solderless-400-pin-breadboard-normal-quality-without-packing/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWeTfoXFAUr9X7EV-4R8c7_6P&gclid=Cj0KCQjwjb3SBhDgARIsAMKiWzj7IYbO3t4JRnmM30mQe9fltd76h3I4cLqhaRUR9IqlDFEWQv-Amu8aAh-tEALw_wcB) | Robu |
| 5 Inch Screen HDMI Interface TFT LCD | The main Display | 1 | 26 | [Link](https://robu.in/product/5-inch-touch-screen-hdmi-interface-display-module-tft-lcd-800x480-raspberry-pi-2-model-b-touch-pen/) | Robu |
| 5mm Led (moq 20) | For the status display | 20 | 0.6 | [Link](https://www.flyrobo.in/pack-25-5-colours-leds-5mm-whiteandgreenandredandyellow-and-blue?tracking=ads&tracking=4a9a9a&gad_source=1&gad_campaignid=17426303996&gbraid=0AAAAAC6AkE_BbI7rZnoPWUn6lRyQkupZq&gclid=Cj0KCQjwjb3SBhDgARIsAMKiWzh5pGBP6x1c4SG6jpgIgAfkHUSNeoK_VtmKZNcPOY6G3kRFQBHTL6QaAobUEALw_wcB) | Flyrobo |
| 40 pin gpio header | For the EEPROM | 4 | 0.5 | [Link](https://robu.in/product/2-54mm-1x40-pin-female-single-row-header-strip-pack-of-10/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWeTfoXFAUr9X7EV-4R8c7_6P&gclid=Cj0KCQjwjb3SBhDgARIsAMKiWzhM2ujRukNeHaKe4-WQ0FSXoJPuGRUneRq1Zqoe6L4hlrBShnfp824aAmNrEALw_wcB) | Robu |
| Blank USB connector | For the usb connection | 3 | 0.2 | [Link](https://robu.in/product/u221-041n-1wz57-f1-xkb-usb-2-0-female-usb-connectors-rohs/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWeTfoXFAUr9X7EV-4R8c7_6P&gclid=Cj0KCQjwjb3SBhDgARIsAMKiWzicpPTGQCcxBl6k4ZelsWKfxqciUnxToxgo_fav-815Y-hWN1h6weMaAlxMEALw_wcB) | Robu |
| Power supply | To power the circuit | 1 | 2.4 | [Link](https://robu.in/product/power-supply-adapter-charger-5v-3a-type-c-plug/) | Robu |
| Micro Hdmi | For the display connection | 1 | 1.5 | [Link](https://robu.in/product/micro-hdmi-to-hdmi-cable/?gad_source=1&gad_campaignid=17416544847&gbraid=0AAAAADvLFWdySOPtzm05zwEjKwn0RN97e&gclid=Cj0KCQjwjb3SBhDgARIsAMKiWzgdZAlJOzNI-Gi63zKhhA9l67AL8OWcViJGdZup442bbvVaeeZY4gAaApIAEALw_wcB) | Robu |
| Tax |  |  | 4.2 |  |  |
| Shipping | incl.PCB |  | 26 |  |  |
| **Total** |  |  | **115.5** |  |  |
| **Round Off Total** | Dollar rate fluctuation |  | **120** |  |  |
