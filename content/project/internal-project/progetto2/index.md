
---
title: Spartacus BackEnd
summary: Modular Motherboard.
tags: 
 - Digital
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page). 
# external_link: "https://audiogearobsession.com/"

image:
  caption: 
  focal_point: Center

links:
# - icon: facebook
#  icon_pack: fab
#  name: Follow
#  url: https://www.facebook.com/AudioGearObsession.Ago
# url_code: "https://audiogearobsession.com/ "
# url_pdf: ""
# url_slides: ""
# url_video: "https://www.youtube.com/watch?v=Fcz6rSpaFNY"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

---



During the last year of Univeristy I worked as an Intern for X-Phase s.r.l. , an Italian company based in Sesto Fiorentino, specialized in advanced electronic system for biomedical and industrial applications such as echographic system, radar and biomedical devices.

My internship (and Thesis) objective was the project and development of signal processing PCB for a modular ultrasound system.
The PCB is a 10 Layer eurocard format 100x160 mm carrier board, compliant to CompactPCI serial specifications, that embeds a NVidia System on Module (Jetson Tx2) and a PCI Express 2.0 Switch, among other serial high speed peripherals.

Here below, a  (partial) list of the features:

- Jetson TX2 SoM (256-core NVIDIA Pascal™ GPU architecture with 256 NVIDIA CUDA cores)
- HDMI
- USB 3.0 & 2.0
- SD CARD
- PCI Express x4
- Gigabit Ethernet
- I2C
- SPI
- JTAG
- eDP Display Connector
- UART
- M2 EVMe Disk


A block scheme of the whole system:
{{< figure library="true" src="schema_a_blocchi2.jpg" lightbox="true" >}}

The board from the EDA tool 3d Viewer (Allegro PCB):
{{< figure library="true" src="featured.jpg" lightbox="true" >}}










