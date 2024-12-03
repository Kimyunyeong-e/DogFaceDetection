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
Tabular Results (CSV):

Query Image	image1.jpg	image2.jpg	image3.jpg	image4.jpg	image5.jpg
sample_data/sample1.jpg	0.89	0.76	0.92	0.65	0.81
sample_data/sample2.jpg	0.75	0.88	0.67	0.80	0.74
sample_data/sample3.jpg	0.68	0.72	0.95	0.78	0.83
Bar Graph Results:

Below is an example bar graph showing the similarity between sample1.jpg and the dataset images.

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

