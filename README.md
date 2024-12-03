# 🐶 Dog Finder Program

## 📖 Project Overview
This project identifies a specific dog from a set of dog images provided by the user. It uses external features of the dog to distinguish it from others, which often appear visually similar. The program was designed with the potential to be applied in scenarios such as stray dog rescue efforts or supporting dog registration systems.

---

## 🎯 Background
- **Stray Dog Rescue**: Helps locate lost dogs efficiently within shelters or from public databases.
- **Dog Registration System**: Assists in verifying registered dogs against a database for identification.
- **Distinguishing Similar Dogs**: Finds unique external characteristics to differentiate visually similar dogs, which can be challenging for humans.

---

## 🚀 Key Features
1. **Dog Image Comparison**:
   - Compares a given query dog image against multiple images in a dataset to identify the most similar one.
2. **Similarity Visualization**:
   - Outputs similarity scores in both tabular and bar graph formats for easier analysis.
3. **Pre-trained Deep Learning Model**:
   - Utilizes MobileNetV2 to extract feature vectors from images.

---

## 🛠️ Technology Stack
- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow, Keras
- **Data Analysis and Visualization**: Pandas, Matplotlib

---

## 📊 Example Output
The Dog Finder Program successfully identifies the most similar dog image from a dataset based on a given query image. The results are presented in both a tabular format and a bar graph for clear visualization.

1️⃣ Tabular Results
The program outputs a table that lists the similarity scores between the query image and each image in the dataset. These scores range from 0 to 1, where a score closer to 1 indicates a higher similarity.

Query Image	image1.jpg	image2.jpg	image3.jpg	image4.jpg	image5.jpg
sample_data/sample1.jpg	0.89	0.76	0.92	0.65	0.81
sample_data/sample2.jpg	0.75	0.88	0.67	0.80	0.74
sample_data/sample3.jpg	0.68	0.72	0.95	0.78	0.83

This table clearly indicates which dataset image is the most similar for each query image.

2️⃣ Graphical Results
For each query image, a bar graph is generated to visualize the similarity scores. The x-axis represents the dataset images, while the y-axis represents the similarity scores. This allows for quick identification of the closest match.


![image](https://github.com/user-attachments/assets/26a0d8f7-0da4-42ca-adec-969c3f6fb90a)

![image](https://github.com/user-attachments/assets/3a917687-6753-4487-8062-54b2909b189c)

![image](https://github.com/user-attachments/assets/47a7c003-fbb6-47e1-ac0b-878406365b77)

3️⃣ Observations
The program efficiently distinguishes between visually similar dogs by analyzing their external features.
High similarity scores (close to 1) indicate a strong match, while lower scores suggest less similarity.
The combination of numerical and graphical outputs ensures clarity and aids in decision-making.

---

## 📌 Use Cases
Stray Dog Rescue: Quickly locate a specific dog from shelter databases or public image repositories.
Dog Registration System: Verify a dog's identity against a registered database.
Dog Similarity Analysis: Analyze external features of dogs to find similarities and differences.

---

## 📄 References 
- FaceNet: A Unified Embedding for Face Recognition and Clustering
- Deep Residual Learning for Image Recognition (ResNet)
- Dog Breed Identification using Deep Learning (Kaggle Challenge)
- A Lightweight CNN Model for Animal Face Recognition
- MTCNN: Joint Face Detection and Alignment using Multi-task Cascaded Convolutional Networks
- OpenFace: Free and Open Face Recognition with Deep Neural Networks
- Transfer Learning for Image Classification with Deep Convolutional Neural Networks

---
## 🐾 Creator
Name: Kim Yunyeong

Email: elaine0222@naver.com

