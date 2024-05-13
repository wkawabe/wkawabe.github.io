---
title: "Interactive 3D Annotation of Objects in Moving Videos from Sparse Multi-View Frames"
excerpt: "Kotaro Oomori, <u><b>Wataru Kawabe</b></u>, Fabrice Matulic, Takeo Igarashi, and Keita Higuchi<br/>Proceedings of the ACM on Human-Computer Interaction, ISS, 2023<br/>[doi](https://dl.acm.org/doi/10.1145/3626476), [video](https://youtu.be/PT-PElgtQcI?si=ExvknLbsv6hNsMYQ)<br/><img src='/images/projects-3.png' width=600>"
collection: projects
---

<img src='/images/projects-3.png'>

[doi](https://dl.acm.org/doi/10.1145/3626476),
[video](https://youtu.be/PT-PElgtQcI?si=ExvknLbsv6hNsMYQ)

Segmenting and determining the 3D bounding boxes of objects of interest in RGB videos is an important task for a variety of applications such as augmented reality, navigation, and robotics. Supervised machine learning techniques are commonly used for this, but they need training datasets: sets of images with associated 3D bounding boxes manually defined by human annotators using a labelling tool. However, precisely placing 3D bounding boxes can be difficult using conventional 3D manipulation tools on a 2D interface. To alleviate that burden, we propose a novel technique with which 3D bounding boxes can be created by simply drawing 2D bounding rectangles on multiple frames of a video sequence showing the object from different angles. The method uses reconstructed dense 3D point clouds from the video and computes tightly fitting 3D bounding boxes of desired objects selected by back-projecting the 2D rectangles. We show concrete application scenarios of our interface, including training dataset creation and editing 3D spaces and videos. An evaluation comparing our technique with a conventional 3D annotation tool shows that our method results in higher accuracy. We also confirm that the bounding boxes created with our interface have a lower variance, likely yielding more consistent labels and datasets.