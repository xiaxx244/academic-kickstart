---
title: "Visual Diver Recognition for Underwater Human-Robot Collaboration"
date: 2018-09-15
publishDate: 2019-05-22
authors: ["Youya Xia", "Junaed Sattar"]
publication_types: ["1"]
abstract: "This paper presents an approach for autonomous
underwater robots to visually detect and identify divers. The
proposed approach enables an autonomous underwater robot
to detect multiple divers in a visual scene and distinguish
between them. Such methods are useful for robots to identify
a human leader, for example, in multi-human/robot teams
where only designated individuals are allowed to command or
lead a team of robots. Initial diver identification is performed
using the Faster R-CNN algorithm with a region proposal
network which produces bounding boxes around the divers’
locations. Subsequently, a suite of spatial and frequency domain
descriptors are extracted from the bounding boxes to create a
feature vector. A K-Means clustering algorithm, with k set to
the number of detected bounding boxes, thereafter identifies
the detected divers based on these feature vectors. We evaluate
the performance of the proposed approach on video footage of
divers swimming in front of a mobile robot and demonstrate
its accuracy."
featured: false
publication: "*2019 IEEE International Conference on Robotics and Automation*"
tags: ["Computer Vision", "Robotics Perception", "Human-Robot Collaboration"]
url_slides: "diver_detection.pdf"
url_video: "https://www.youtube.com/watch?v=rbsOBoG2QeM&feature=youtu.be"
url_code: "https://github.com/xiaxx244/diver_detection"

---
