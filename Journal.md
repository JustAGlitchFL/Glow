---
title: "Glow"
author: "rowyn"
description: "Modular interconnected lighting system for videography"
created_at: "2024-05-28"
---

## 5/28/2025: Ideation and planning
3 hours

I first got the idea for this project from a fusion of planning my dorm room for college, and buying a Fujifilm X-M5 for photography and videography. Lighting is a crucial part of getting a good image. Additionally, I also wanted a very functional and repositionable desk lamp for working on projects. The combination of wanting decent lighting for filming myself at my desk, decent lighting for projects, battery powered accent lighting for interesting photos and videos, and space saving led me to combine all of these. The general concept of this is a diffused panel of LEDs with both adjustable temperature white and full RGB control. It will be powered either through battery of USB-C for portability, and be mounted on a quarter/20 thread to use various mounts, and fit into a standard shoe to use on camera. These lights will be connected wirelessly, so settings can be changed on one light and linked to the others. Connecting a panel to the camera's hot shoe allows it to be used as a flash, and to trigger the other panels at the same time. The thread can also be used to mount it to an IKEA LÅNESPELARE arm, turning it into a repositionable desk lamp, or a key light for desk filming (I also plan to put the X-M5 on another as a versatile desk mount, while my existing microphone currently sits supported by a similar arm as I write this.)

## 6/16-6/20: Figuring out wtf to do
4 hours

I was trying to figure out how in the world I wanted to build this; whether to use RGBW neopixels, RGB neopixels combined with natural white separate leds, larger COB tunable color temperature leds with RGB neopixels, or trying to source RGBCCT neopixels not on a strip (RGB, cool white, warm white). Eventually, for the sake of simplicity, I chose to go with RGBW neopixels, as I would not need any complex driver circuitry, and they can be controlled as standard neopixels. I'm not super concerned about tunable color temperature, as I mostly just want a natural white, and can compensate for temperature using my Nanoleaf panels on my wall as a fill light when shooting talking head content at my desk. I'm also dropping the wireless connectivity, as I think it's kind of pointless. I also would like to make some of these as task/accent lighting at Open Sauce for the Hackclub booth, so simplicity and rapid assembly is important here.

## Night of 6/21
2 hours

I thought up the layout and rough format of the device, and chose LED modules, microcontrollers, LiPo charging ICs, and control switches to use for this.

## 6/21: Schematic and start of PCB
4 hours
![](/images/sch.png)

## 6/22: Finishing the pcb
3 hours
rerouted like 5 times after I realized it would be significantly easier to put all the SMD components on one side for hot plate assembly.
![](/images/pcb.png)

## 6/23: Case
2 hours
onshaped a case
![](/images/case.png)

## 7/21: Back from Montana and actually getting around to submitting it
3 hours
BOM, finishing journal, submitting, etc
