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

## June 16, charge circuit!!!
For today i wanted to implement a lipo into the design and find a way to charge it. I first looked at all the cells avail and noticed 3.7V was the most common so i decided to get that, however the rp2040 only accepts 5v and heres where a boost converter comes in! The mt3608 converts my 3.7v battery into usable 5v through two resistors. I also decided to use the tp4056 battery ic in this project as it was cheap in lscs.
![image](https://github.com/user-attachments/assets/71ab6e1e-6039-46e6-bb1c-2aa60e9aaaca)
ps kinda running out of spaceeeee

**time spent ~4ish hours


## June 29, BOM and getting ready for PCB!!
Woww I took a long ass break, welp it was worth it cuz I recent had summer camp as well as starting my RTX internship WOOO!!!. Anyways today I focused mainly on searching up all my parts on jlc/lscs and writting that in one notepad doc :( this rlly took alot of time and im glad thats all over!!! Ive also converted the easyeda footprints to kicad too so it would masivly help in assigning foorprints the next time i work on this!

ughhh im so tired
![image](https://github.com/user-attachments/assets/8fb8adbb-1203-4af3-a3d1-0185a08c4394)
ps my search history is fully of jlcpcb omg 

**time spent  ~5 hours**
