---
layout: page
title: IoT Badge System
description: 2-layer Authentication IoT System (Badge + Visual Recognition)
img: assets/img/iot-front.png
importance: 1
category: work
related_publications: true
---

This project involves the development of a 2-layer authentication IoT system that combines NFC/RFID badge detection with facial recognition. The system is designed to enhance security by requiring both badge scanning and facial verification for user authentication.

Key features include:

- Integration of NFC/RFID badge reader and Pi Camera on a Raspberry Pi 3.
- Implementation of facial recognition using OpenCV.
- Development of a user-friendly interface for registration and monitoring.
- Real-time authentication and attendance tracking.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/iot-use.png" title="Badge Reader Setup" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/iot-diagram.png" title="System Architecture" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Left: NFC/RFID badge reader connected to Raspberry Pi. Right: Overall system architecture diagram.
</div>

For more information, check out the [GitHub repository](https://github.com/nhathuy25/iot-badge-system).
