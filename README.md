# AICrowd-Mosquito 🦟

## 🌟 Welcome to the Mosquito Challenge!
Hello there! 👋 Excited to have you on board for the AICrowd Mosquito Challenge. We're diving into an intriguing task: classifying mosquitoes from phone camera images. 📸 It's a crucial step in combating diseases like Zika, Dengue, Malaria, and Chikungunya carried by these tiny mosquitoes.

## 🧐 What's This All About?
- **Objective**: Classify mosquitoes into six categories: 
  - 🦟 **Aedes aegypti**
  - 🦟 **Aedes albopictus**
  - 🦟 **Anopheles**
  - 🦟 **Culex**
  - 🦟 **Culiseta**
  - 🦟 **Aedes japonicus/Aedes koreicus**


## 🚀 The Challenge
1. **Mosquito Detection**: Detecting these small mosquitoes (small object detection).
2. **Mosquito Classification**: Classifying the detected mosquitoes into the specified categories.


## 📉 The Twist: Imbalance in Data
- **Big Challenge**: A whopping 88.6% of our data belong to just Aedes albopictus and Culex classes . 


## 💡 Solution
1. **External Data**: Obtained additional images from [GBIF](https://www.gbif.org/) to reduce the imbalalnce in the dataset.
2. **Data Augmentation**: Implemented various augmentation techniques to increase the minority classes' sample size.


## 📊 Evaluation Metric?
- **Filtered Macro F1 Score** is our go-to metric, considering the data imbalance.


## 📈 Our Approach & Results
1. **Detection**: Utilized YOLOv5s due to resources limitation, achieving a mAP50 of 0.972 and mAP50-95 of 0.743. 🎯
2. **Classification**: Post-detection, we classified the mosquitoes, with a Macro F1 Score of 0.559 at 0.75 IOU. Ranked 24th on the leaderboard! 🌟

---

**TL;DR**: 🦟 Join us in tackling the AICrowd Mosquito Challenge! We're using phone pics to classify mosquitoes, dealing with data imbalance. Ranked 24th with some not-too-shabbt stats! 🚀🔍