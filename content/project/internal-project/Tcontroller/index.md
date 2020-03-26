---
title: T-Controller
summary: Bluetooth Temperature Controller.
tags:
 - Digital
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page). 
# external_link: "https://audiogearobsession.com/"

image:
  caption: 
  focal_point: Smart

links:
 # - icon: facebook
  # icon_pack: fab
  # name: Follow
  # url: https://www.facebook.com/AudioGearObsession.Ago
  # url_code: "https://audiogearobsession.com/ "
  # url_pdf: ""
  # url_slides: ""
  # url_video: "https://www.youtube.com/watch?v=Fcz6rSpaFNY"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
This is a DIY experiment, the idea behind this project is the temperature monitoring for a BBQ. The system is based on a thermocouple IC which sends the thermocouple data to a STM32L4 Microcontroller, the microntroller then transmits the data out  to a Blueotooth HC06 Module. The board can be powered from the 5V Usb connector or from a lithium battery. The board includes  battery charger & fuel gauge circuits. A small Oled 128 x 64 is present on the PCB for a visual indication of the temperature.

I've used Altium Designer for the board design and STMCubeIDE for the firmware develpment.

PCB on Altium:
{{< figure library="true" src="TController_board.jpg" lightbox="true" >}}

Soldered PCB:
{{< figure library="true" src="photo1.jpg" lightbox="true" >}}










