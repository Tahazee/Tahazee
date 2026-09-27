# Taha Zeeshan

### AI/ML & Robotics | Computer Vision | Autonomous Systems

Computer Engineering student building real-time AI, computer vision, and autonomous robotics systems.

## About

- AI/ML, Computer Vision & Robotics
- Deep Learning, Object Detection & Semantic Segmentation
- Stereo Vision, Depth Estimation & Visual Odometry
- SLAM, Sensor Fusion & Autonomous Navigation
- Real-time Edge AI on Jetson and Raspberry Pi
- AI/ML research and applied computer vision

## Technical Stack

### AI / Machine Learning

Python, PyTorch, TensorFlow, Keras, scikit-learn, YOLOv8, Anomalib  
CNNs, CAEs, ResNet, EfficientNet, U-Net

### Computer Vision

OpenCV, Grounding DINO, OWL-ViT, CLIP, ZED SDK  
Stereo Vision, Depth Estimation, Camera Calibration, Object Detection, Semantic Segmentation

### Robotics & Autonomous Systems

ROS2 Humble, Nav2, SLAM Toolbox, RTAB-Map, ORB-SLAM3  
TF2, Pangolin, EKF, MAVLink, PyMAVLink, LiDAR, Sensor Fusion

### Hardware

NVIDIA Jetson Orin Nano, Raspberry Pi 5, ZED 2, ZED Mini  
RPLiDAR A1, IMX219 Stereo Camera, Pixhawk

### Development & Infrastructure

Python, C++, C#, SQL  
Git, Linux, Docker, CUDA, FastAPI, PostgreSQL, Redis, Qdrant

---

# Featured Projects

## iGlasses — Edge AI Assistive Vision

Real-time assistive vision and navigation system for visually impaired users.

- Built stereo perception using an IMX219 stereo camera, including calibration, rectification and depth estimation.
- Generated 2D occupancy grids and integrated depth information for real-time obstacle-aware navigation.
- Fine-tuned YOLOv8 for traffic-light and obstacle detection and integrated detections with stereo depth.
- Developed voice-assisted interaction, emergency response and real-time navigation capabilities.
- Designed the system for low-latency edge inference and real-time operation.

**1st Place — Engineering Project Exhibition**  
**3rd Place — Youth Tech Begin**  
**₺30,000 Prize**

---

## Ulurover — Autonomous Rover

Autonomous mobile robotics platform focused on SLAM, localization, perception and navigation.

- Developed autonomous navigation using ROS2 Humble, RPLiDAR A1, SLAM and Nav2.
- Built a custom stereo-vision pipeline using ZED 2 and ORB-SLAM3 for visual localization and odometry.
- Integrated IMU and visual odometry using EKF sensor fusion and used Pangolin for real-time SLAM visualization.
- Implemented mapping, localization, TF2 transformations, path planning, costmaps and obstacle avoidance.
- Validated the system through 50+ navigation experiments and achieved approximately 35% reduction in localization drift.

---

## Industrial Anomaly Detection

Unsupervised industrial defect detection using a custom convolutional autoencoder.

- Trained exclusively on defect-free MVTec AD images without using anomalous samples during training.
- Compressed 900×900 images into an 8-dimensional latent representation and reconstructed the original image through a decoder.
- Used reconstruction error as the anomaly score for detecting previously unseen industrial defects.
- Implemented using PyTorch, CNNs, Autoencoders and MVTec AD.

---

## Weakly Supervised Semantic Segmentation

U-Net-based semantic segmentation using limited point-level supervision on aerial imagery.

- Trained a U-Net segmentation model using partial annotations rather than complete pixel-level masks.
- Compared training with only 5, 10 and 50 annotated pixels per image.
- Evaluated segmentation using Intersection over Union (IoU) and analyzed the impact of sparse supervision on object boundaries and small structures.

---

# Research Interests

Computer Vision, Vision-Language Models, Multimodal AI, Object Localization, Autonomous Systems, SLAM, Edge AI

---

# Education

**B.Sc. Computer Engineering**  
Bursa Uludağ University

**Erasmus+ — B.Sc. Software Engineering**  
Heilbronn University of Applied Sciences

---

# Contact

LinkedIn: [linkedin.com/in/tahazeeshan](https://linkedin.com/in/tahazeeshan)

Portfolio: [tahazee.github.io](https://tahazee.github.io)

Email: tahazeeshan09@gmail.com
