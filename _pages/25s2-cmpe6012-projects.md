---
layout: page
permalink: /teaching/cmpe6012-25s2/
title: 2025 Semester 2 CMPE6012 Student Projects
description: Student project showcase for the 2025 Semester 2 delivery of CMPE6012 - Artificial Intelligence and Machine Learning in Embedded Systems
nav: false
---

## CMPE6012 - Artificial Intelligence and Machine Learning in Embedded Systems

This page presents final projects from the **2025 Semester 2** delivery of [CMPE6012: Artificial Intelligence and Machine Learning in Embedded Systems](https://handbook.curtin.edu.au/units/unit-pg-artificial-intelligence-and-machine-learning-in-embedded-systems--cmpe6012v1).

These Embedded AI/ML projects demonstrate the successful translation of fundamental Machine Learning concepts into practical, real-time solutions. Throughout the unit, students were guided to leverage state-of-the-art pre-trained models to address real-world challenges on resource-constrained embedded platforms. By optimizing and deploying these models on NVIDIA Jetson hardware, students have provided tangible evidence of their proficiency in Edge AI, inference acceleration using TensorRT, and hardware-software co-design (skills highly valued in modern intelligent systems engineering).

*We acknowledge the dedication, technical innovation, and professional engagement demonstrated by the entire cohort.*
<p style="text-align:center;">
  <img src="/assets/img/cmpe6012_25s2_photo.jpg" alt="CMPE6012 25S2" style="max-width:100%;height:auto;" />
</p>

<br>

### Project 1 - Smart Home System using Gesture Control with NVIDIA Jetson Nano
- **Students:** Arju Dharsandiya, Wendy Amoah, Avanti More, Guruprakash Arun
- **Brief Summary:** This project presents the design and implementation of a real-time gesture-controlled system using the NVIDIA Jetson Orin Nano and Arduino Uno for human–machine interaction. The system enables intuitive, touch-free control of external devices by recognizing four predefined hand gestures Open Palm, Closed Fist, Thumbs Up, and Thumbs Down captured via a webcam and processed using deep learning–based computer vision. In the first phase, the MediaPipe YOLOv8n-hand.pt model was deployed to perform 21-point hand landmark detection in real time. In the second phase, the same model was converted to ONNX and optimized into a TensorRT FP16 inference engine to enhance speed and efficiency on the Jetson GPU. A communication interface between the Jetson and Arduino enabled serial command transmission for controlling LEDs and servo actuators corresponding to detected gestures. Comprehensive performance evaluation demonstrated near-perfect precision, recall, and F1-scores (~1.0) across both implementations, confirming consistent classification accuracy. The TensorRT-optimized model achieved an average inference latency of 6.1 ms compared to 44.3 ms for the baseline, representing an ~86% reduction in processing time. Real-time visualization with live latency and FPS overlays validated smooth, low-latency operation and responsive device control. The results confirm that TensorRT-based deployment significantly enhances inference speed while maintaining model integrity, enabling robust, low-power, and real-time gesture recognition on embedded platforms. The proposed system demonstrates strong potential for smart-home automation, industrial control, and assistive technology applications, where responsive and reliable human–machine interaction is essential.
- **Demo Video:**
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;">
  <iframe src="https://www.youtube.com/embed/5q1MoAnBtlE?si=SK5VMyLKVFZ4i4ld" title="Project 1 Demo" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<br>

### Project 2 - Obstacle Avoidance and Navigation Device for Blind and Visually Impaired People
- **Students:** Md Sihab Uddin, Ibtihaj Rahman, Zehao Pei, Muhammad Mujtaba Zuberi
- **Brief Summary:** Visual impairment greatly affects mobility and independence, with the World Health Organization reporting over 285 million visually impaired individuals worldwide, including 39 million who are completely blind. To address these challenges, numerous wearable and portable assistive technologies have been developed to enhance safety, orientation, and autonomy. Yet, many of these systems remain limited by short detection ranges, high costs, bulky designs, and poor adaptability to diverse environments. This case study examines the design and evaluation of an Obstacle Avoidance and Navigation Device for Blind People, emphasizing its potential to address the limitations of current solutions. The device combines ultrasonic sensors with microcontroller-based processing and multimodal feedback mechanisms, such as haptic and auditory cues, to provide real-time obstacle detection and navigation support. Through a comparative review of existing technologies, this study highlights improvements including lightweight construction, lower power consumption, and enhanced accuracy in dynamic settings. The findings suggest that effective systems must balance technical efficiency with user-focused factors such as comfort, affordability, and ease of use. This case study contributes insights for developing next-generation assistive devices that promote safe, independent mobility for blind and visually impaired individuals.
- **Demo Video:**
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;">
  <iframe src="https://www.youtube.com/embed/2p3dW-uSBW0?si=P7EIWuMx5e6eTgJh" title="Project 2 Demo" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<br>

### Project 3 - Embedded AI for Livestock Monitoring
- **Students:** Dong Liang, David Kajwang, Srivatsa Tata
- **Brief Summary:** This project presents an edge-computing solution for real-time livestock monitoring. Using NVIDIA's DeepStream SDK on a Jetson Orin Nano, the system processes multiple camera feeds, tracking individual animals with persistent IDs while consuming only 15W of power. The solution supports wirelessly connected cameras while providing a web dashboard for real-time metrics. By leveraging TensorRT optimization to compress YOLO models and implementing GPU processing pipelines, the system achieves commercial-grade performance at a fraction of the cost. Testing demonstrates reliable operation with features including multi-zone analytics and GPIO-triggered physical alerts. This work proves that production-ready agricultural AI can be implemented with thoughtful application of existing tools. The implementation achieves performance improvement over baseline Pytorch implementation while reducing model size through optimization.
- **Demo Video:**
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;">
  <iframe src="https://www.youtube.com/embed/sIAt2lbc-ZM?si=TO5VSZiwQwweGj8-" title="Project 3 Demo" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

- **Code:** [GitHub Repository](https://github.com/harrydleung/Curtin-CMPE6012-Final-Project)
