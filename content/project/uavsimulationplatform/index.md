---
title: UAV Simulation Platform
summary: C++, QT, UDP, AirSim
tags:
- SoftwareDevelopment
date: "2020-04-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
### Description
It is a platform simulating UAV flight based on AirSim. The structure can be illustrated in the following grapg.
{{< figure src="structure.png" title="System Structure" >}}
In this system, you can control a drone in control panel, such as takeoff, land and move. The drone can move in the simulation platform backed by AirSim according to the operations in control panel. The real-time position data of drone can be sent to MATLAB by UDP protocol and the 3D trajectory of drone can be drawn. 
The simulation and control panel are shown in the following picture.
{{< figure src="uav.jpg" title="UAV Simulation" >}}
