<h1 align="center">
  ୨୧ hi, i'm Joanna ♡
</h1>

<p align="center">
  <i>AI, embedded systems & little things that make me go "yippie it works" ✦</i>
</p>

<p align="center">
  ⋆｡°✩ ─────────────── ✩°｡⋆
</p>

<p align="center">
  ♡ computer engineering student · specialized in embedded systems · ML/AI enthusiast · artist ♡
</p>

---

## ˚₊‧꒰ა about me ໒꒱ ‧₊˚

୨୧ I'm a computer engineering student in Mapúa University interested in **Artificial Intelligence, Machine Learning, Computer Vision, Embedded Systems, and IoT**.

୨୧ I especially enjoy projects where **software meets hardware** — working with sensors, cameras, microcomputers, and physical systems.

୨୧ Currently learning how to make intelligent systems that can actually run and interact with the real world ♡

---

## 🎀 currently...

- 🔭 **I’m currently working on**

  **Aquaponic Monitoring System with Gradient Boosting Machine Image Analysis for *Ipomoea aquatica*** 🌱🐟

  A Raspberry Pi 4-based aquaponic monitoring system that combines **embedded systems, environmental sensing, image processing, and machine learning**.

  The system uses a **BH1750 light sensor, DS18B20 temperature sensor, DFRobot analog pH sensor, ADS1115 ADC, and Raspberry Pi Camera Module v2** to monitor environmental conditions and capture images of kangkong leaves.

  For the computer vision side, I'm working with **OpenCV** to segment leaf images and extract color, texture, edge, and engineered features. These features are then passed to a **Gradient Boosting Machine (GBM)** to classify leaves as:

  `♡ Healthy` · `♡ Discolored` · `♡ Diseased`

  The project uses a **571-element image feature vector** and a GBM trained with scikit-learn. The final model achieved **93.53% test accuracy** and a **0.9363 macro-F1 score** on 139 held-out images.

  One of the parts I particularly enjoyed was deploying the model on the **Raspberry Pi itself**. Random Forest achieved higher offline accuracy, but GBM had lower inference latency on the Raspberry Pi, making it the model selected for deployment.

- 🌱 **I’m currently learning**

  More **machine learning techniques, computer vision, and embedded AI**.

  I'm especially interested in how machine learning models can be adapted for **resource-constrained hardware**, instead of only running in a traditional desktop or cloud environment.

  I'm also learning more about **real-time inference, model optimization, feature engineering, sensor-data integration, image processing, and deploying AI models on embedded devices**.

  Basically:

  `AI` + `Hardware` + `Sensors` + `Computer Vision` = ♡

- 👯 **I’m looking to collaborate on**

  **IoT · Embedded Systems · Artificial Intelligence · Machine Learning · Computer Vision**

  I'm especially interested in projects where hardware and software have to work together. ୨୧

- 📫 **How to reach me**

  We can be mutuals ♡

  <p align="center">

  <a href="mailto:joannadulay.ph@gmail.com">
    <img src="https://img.shields.io/badge/Email-joannadulay.ph%40gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white">
  </a>

  <a href="https://cjx20000.my.canva.site/joanna-dulay-portfolio">
    <img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=canva&logoColor=white">
  </a>

  <a href="https://www.linkedin.com/in/mary-joanna-dulay-2oo3">
    <img src="https://img.shields.io/badge/LinkedIn-A855F7?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>

  <a href="https://www.instagram.com/joanna.dulay/?hl=en">
    <img src="https://img.shields.io/badge/Instagram-C084FC?style=for-the-badge&logo=instagram&logoColor=white">
  </a>

  </p>

- 😄 **Pronouns:** she/her

- ⚡ **Fun fact**

  I love **psychological horror** and **true crime documentaries** 🕯️

  I listen to **Paramore** and **Deftones** <3

  And I love doing **art** as both a hobby and a passion 🎨

---

<p align="center">
  ୨୧ ─────────── ⋆｡°✩ ─────────── ୨୧
</p>

## 💜 my little tech corner

<p align="center">

<img src="https://img.shields.io/badge/Python-8B5CF6?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/C++-A855F7?style=for-the-badge&logo=cplusplus&logoColor=white">
<img src="https://img.shields.io/badge/Arduino-7C3AED?style=for-the-badge&logo=arduino&logoColor=white">
<img src="https://img.shields.io/badge/Raspberry%20Pi-9333EA?style=for-the-badge&logo=raspberrypi&logoColor=white">

</p>

<p align="center">

<img src="https://img.shields.io/badge/OpenCV-8B5CF6?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-A855F7?style=for-the-badge&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-7C3AED?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/Git-9333EA?style=for-the-badge&logo=git&logoColor=white">

</p>

---

## 🪻 featured project

### ୨୧ Aquaponic Monitoring System

**Aquaponic Monitoring System with Gradient Boosting Machine Image Analysis for *Ipomoea aquatica***

<p align="center">
  <img src="./assets/aquaponic-system.jpg" width="650">
</p>

<p align="center">
  <i>♡ the actual aquaponic prototype ♡</i>
</p>

<br>

<p align="center">
  <img src="./assets/aquaponic-hardware.png" width="800">
</p>

<p align="center">
  <i>୨୧ hardware architecture & component layout ୨୧</i>
</p>

### ♡ about the project

A Raspberry Pi-based system combining **real-time environmental monitoring** with **machine-learning-based leaf health analysis** for *Ipomoea aquatica* (kangkong), with *Oreochromis niloticus* (tilapia) as a supplementary indicator species.

The system continuously monitors:

`☀ Light Intensity` · `🌡 Water Temperature` · `💧 pH`

while a camera captures kangkong leaf images for machine-learning analysis.

The system then combines the environmental readings with the image-analysis results and presents the results through a touchscreen interface.

### ♡ hardware

`Raspberry Pi 4 Model B`  
`BH1750 Digital Light Intensity Sensor`  
`DS18B20 Temperature Sensor`  
`DFRobot Gravity Analog pH Sensor`  
`ADS1115 16-bit ADC`  
`Raspberry Pi Camera Module V2`  
`5-inch Touchscreen LCD`

### ♡ software

`Python` · `OpenCV` · `scikit-learn` · `Tkinter` · `Pillow`

### ♡ image analysis pipeline

```text
       ♡ leaf image
            ↓
     HSV segmentation
            ↓
 morphological processing
            ↓
 connected-component analysis
            ↓
  feature extraction
            ↓
    571 image features
            ↓
 Gradient Boosting Machine
            ↓
 ┌──────────┼──────────┐
 ↓          ↓          ↓
Healthy   Discolored  Diseased
