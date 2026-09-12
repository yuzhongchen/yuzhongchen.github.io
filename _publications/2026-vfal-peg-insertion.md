---
title: "Vision-Force Admittance Learning for Peg Insertion into a Movable Hole"
collection: publications
category: manuscripts
permalink: /publication/2026-vfal-peg-insertion
excerpt: 'A Vision-Force Admittance Learning (VFAL) framework that fuses asynchronous visual feedback with a high-frequency force-based model for precise peg-in-hole insertion in dynamic environments.'
date: 2026-01-01
authors: '**Yuzhong Chen**<sup>1</sup>, [Yongqing Liang](https://lyq.me/scholar)<sup>1</sup>, Yunzhi Xu<sup>2</sup>, [Irving Fang](https://irvingf7.github.io/)<sup>1</sup>, Chase Kidder<sup>2</sup>, Hui-ping Wang<sup>2</sup>, Raihan Haque<sup>2</sup>, Yubiao Zhang<sup>2</sup>, [Chen Feng](https://scholar.google.com/citations?user=YeG8ZM0AAAAJ)<sup>1&#9993;</sup>'
note: '<sup>1</sup>New York University &nbsp;&nbsp; <sup>2</sup>General Motors &nbsp;&nbsp; (&#9993;: corresponding author)'
venue: 'IEEE Robotics and Automation Letters (RA-L)'
highlight: 'VFAL fuses asynchronous visual pose estimates from vision foundation models with a high-frequency force-based admittance model, adapting the insertion strategy online to a moving hole while keeping millimeter-level precision, with failure-recovery mechanisms for added robustness.'
header:
  teaser: 'vfal-teaser.gif'
paperurl: '/files/VFAL_RAL2026.pdf'
projecturl: 'https://ai4ce.github.io/VFAL/'
arxivurl: '#'   # TODO: replace with the real arXiv link once the preprint is posted
# codeurl: 'https://github.com/ai4ce/VFAL'      # TODO: uncomment once the code is released
citation: 'Chen, Y., Liang, Y., Xu, Y., Fang, I., Kidder, C., Wang, H.-P., Haque, R., Zhang, Y., & Feng, C. (2026). Vision-Force Admittance Learning for Peg Insertion into a Movable Hole. IEEE Robotics and Automation Letters (RA-L).'
---

Precise manipulation in dynamic environments, whether induced by a mobile robot base or a
target with unknown motion, remains a major challenge in robotics. Manipulation in dynamic
environments introduces substantial uncertainty, which fundamentally conflicts with the tight
precision requirement of precise tasks such as peg-in-the-hole. We propose a
**V**ision-**F**orce **A**dmittance **L**earning (**VFAL**) framework that fuses asynchronous
visual feedback with a high-frequency force-based model, using visual pose estimations as a
regularization term. VFAL adapts insertion strategies online to dynamic motion while maintaining
millimeter-level precision. To obtain robust, low-frequency pose information, we employ
state-of-the-art vision foundation models for visual pose estimation. Additionally, we incorporate
failure recovery mechanisms to enhance overall robustness. We validate our approach in real-world
experiments, demonstrating high success rates and strong adaptability to various pegs and dynamic
environments.
