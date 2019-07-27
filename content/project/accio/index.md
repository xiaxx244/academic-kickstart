---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Accio"
summary: "In this report we demonstrate the methodology of multi-robot collaboration, human-robot interaction and discussing the challenges we faced in this project and the insights gained from them, to be applied to future work in this domain."
authors: [Youya Xia, Yingxin Wei, Xiaofei Chen and Ziqian Qiu]
tags: [Human-Robot collaboration,Robotics Perception,Robotics Manipulation,Computer Vision]
categories: [Project]
date: 2018-12-15

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "experimental result"
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "files/Accio_a peek into multi-robot collaboration and human robot interaction.pdf"
url_slides: "files/accio.pdf"
url_video: "https://www.youtube.com/watch?v=mtgxzt3nx1k"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Accio is the incantation of summoning charm originated from our favourite book, ‘Harry Potter’. Witches uttering the spell of ‘Accio Firebolt’ would call the required broomstick to fly into their hands. Inspired by this magic, we come up with the idea of request things orally and have them delivered to us by robots. The job is designed to be accomplished as the result of collaboration of two robots, Turtlebot and Baxter.

Firstly, Turtle is told what is wanted among the 6 classes chosen. Then it goes to Baxter, and sends it the corresponding index of the desired class. After this, the deep neural network is triggered to train images and the resulting model is adapted to detect different objects appeared on the table. The process returns the coordinates of the desired object. Then Baxter grabs it by implementing inverse kinematics and puts it on Turtlebot. Turtlebot will wait until it gets the object, and then takes the object back to the commander.

To accomplish this task, we divided it into five segments, which are speech recognition, object detection, baxter manipulation, turtlebot motion as well as communication issues.
