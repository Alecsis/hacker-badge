---
title: "Custom Hacker Badge"
author: "Joseph Dang"
description: "Inspired from the github universe badges, I am trying to create a custom hardware badge that features a custom pcb, e ink display, and bluetooth/nfc support!"
created_at: "2025-06-13"
---



## June 13, the brainstorm

Today I wanted to create something new that involved pcb design and programming. I've decided to settle on creating an e-ink badge for conventions/meets and how it can be fully customizable. It would also serve as a practice project before creating a music player/stand that I have in mind. I have pulled inspo from the badger 2040 and the github badger(both images below)  
![badgr](https://github.com/badger/home/blob/main/readme_badgephoto.jpg) 
![gh](https://github.com/user-attachments/assets/b6a36ba9-a2c5-442e-8761-30f299360121)

heres the functions that I plan to have:
- 2.9 display, (296 x 128 pixels)
- flash storage 
- customizable buttons + boot/reset
- leds (maybe)
- lipo and charge circit(jst connector)
- can be programmed in c++ and micropython or fancy website for configs

so far I focused on scoping ideal functions and planning out all the features that I would want. I've used a rp2040 before and it was kinda fun!

**time spent ~1hour ish**
## June 14, the planning
Right now, I've got a barebone rp2040 mcu setup as well as the hardware needed to communicate to a ffc data cable from the screen. This took a lot of planning since its been a while since i've tinkered with embedded electronics. I was at first thinking to use smth like a xiao rp2040 but decided i wanted to challenge myself and gone thru this route. I was also thinking about using a display that aready had a display hat on it, but was it was super expensive($20-40)

Thats all for now!!!

![image](https://github.com/user-attachments/assets/4a6a0c9a-aab4-4414-a540-1ad67101e5ee)
![image](https://github.com/user-attachments/assets/8190d4dc-9d69-4962-9bf6-6fc6317cc109)

ps holy hierarchical sheets r so cool
**time spent ~6 hours ish**AA
