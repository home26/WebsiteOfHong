---
title: HongMarket Online Shopping Website
summary: Spring Boot, AWS, MySQL, MyBatis, Maven, RabbitMQ
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
It is a website where users can buy products and pay online. Alipay and WeChat pay interfaces can be called to pay the products. The system architecture is as follow.
{{< figure src="ArchitectureOfHongMarket.png" title="System Architecture" >}}
Users can select products, place orders and pay online in e-shopping platform. The e-shopping platform can communicate with servers deployed in AWS. The servers can communicate with MySQL database deployed in AWS RDS. The entire project was deployed in AWS Cloud. It is a good exposure to AWS Cloud technology. Spring Boot, AWS, MySQL, MyBatis, Maven and RabbitMQ were used. 
The database architecture is as follow
{{< figure src="DatabaseDesign.png" title="Database Architecture" >}}
### My Contribution
I was responsible for designing, developing and testing this system.
### Project links
Experience link: www.hongmarket.ca <br/>
Front end repo: https://github.com/home26/hongmarket <br/>
Back end repo: https://github.com/home26/hongmarketbackend <br/>
Payment back end repo: https://github.com/home26/hongmarketpayment <br/>
Document (architecture, APIs, database design, etc.) repo: https://github.com/home26/hongmarketdoc
