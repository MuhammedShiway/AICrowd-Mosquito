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

![AI Crowd Outline](./AI%20Crowd%20Outline.png)

## 🚀 The Challenge
1. **Mosquito Detection**: Detecting these small mosquitoes (small object detection).
2. **Mosquito Classification**: Classifying the detected mosquitoes into the specified categories.


## 📉 The Twist: Imbalance in Data
- **Main Challenge**: A whopping 88.6% of our data belong to just Aedes albopictus and Culex classes . 


## 💡 Solution
1. **External Data**: Obtained additional images from [GBIF](https://www.gbif.org/) to reduce the imbalance in the dataset.
2. **Data Augmentation**: Implemented various augmentation techniques to increase the minority classes' sample size.


## 📊 Evaluation Metric?
- **Filtered Macro F1 Score** is our go-to metric, considering the data imbalance.


## 📈 Our Approach & Results
1. **Detection**: Utilized YOLOv5s due to resources limitation, achieving a mIoU of 0.82. 🎯
2. **Classification**: Post-detection, we classified the mosquitoes, with a Macro F1 Score of 0.559 at 0.75 IOU. Ranked 24th on the leaderboard! 🌟

## References
1. Ong, SQ., Ahmad, H., Nair, G. et al. Implementation of a deep learning model for automated classification of Aedes aegypti (Linnaeus) and Aedes albopictus (Skuse) in real time. Sci Rep 11, 9908 (2021). https://doi.org/10.1038/s41598-021-89365-3
2. Song-Quan Ong. (2022). <i>Mosquito on human skin</i> [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DS/2368136
3. John Palmer John Palmer E-mail: john.palmer@upf.edu ORCID: 0000-0002-2648-7860 Role: principal investigator Affiliation: Universitat Pompeu Fabra (UPF) , John Palmer, Frederic Bartumeus Frederic Bartumeus E-mail: fbartu@ceab.csic.es ORCID: 0000-0001-6908-3797 Role: principal investigator Affiliation: Institució Catalana de Recerca i Estudis Avançats (ICREA) , Frederic Bartumeus, Roger Eritja Roger Eritja E-mail: r.eritja@creaf.uab.cat ORCID: 0000-0001-5749-8370 Role: entomology expert Affiliation: Centre de Recerca Ecològica i Aplicacions Forestals (CREAF) , Roger Eritja, Joan Garriga Joan Garriga E-mail: jgarriga@ceab.csic.es ORCID: 0000-0002-4561-7835 Role: corresponding author Affiliation: Centre d'Estudis Avançats de Blanes (CEAB) & Joan Garriga (2021). Mosquito Alert Image Dataset. BioStudies, S-BIAD249. Retrieved from https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD249
4. GBIF.org (04 August 2023) GBIF Occurrence Download https://doi.org/10.15468/dl.c8g29m
5. Couret, Jannelle (2020). Malaria vector mosquito images [Dataset]. Dryad. https://doi.org/10.5061/dryad.z08kprr92


---

**TL;DR**: 🦟 We tackled the AICrowd Mosquito Challenge using phone pics to classify mosquitoes, and handling data imbalance. Ranked 24th with some not-too-shabby stats! 🚀🔍
