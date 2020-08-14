---
title: Agricultural Monitoring System Based On Internet of Things(IoT)
summary: IoT, Cloud, Wireless Sensor Network
tags:
- SoftwareDevelopment
date: "2018-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
### Description
It is a system which can monitor the real-time data of plants. The system structure can be illustrated in the following figure.
{{< figure src="structure.png" title="System Structure" >}}
The sensor nodes can collect data of plants, such as humidity, temperature and real-time photo. They can send the data to gateway by ZigBee protocol. The gateway can transfer the data to cloud server by Wi-Fi protocol. Users can view the visualized real-time data of plants in their mobile phone app remotely. Moreover, when the plants need water, this system can water the plants automatically.  
