# Pneumonia Detection using Chest X-ray Images

Pneumonia is an inflammatory condition primarily affecting the lungs, characterized by symptoms such as cough, chest pain, fever, and difficulty breathing. The goal of this project is to develop an automated system for detecting and classifying pneumonia in medical images.

![Symptoms of Pneumonia](https://user-images.githubusercontent.com/65142149/215302250-841fde71-e182-4ffd-8036-625a3a717de7.png)

## Motivation
The motivation behind this project is to leverage artificial intelligence to accurately detect and classify pneumonia in humans using chest X-ray images. By automating the diagnosis process, it can aid healthcare professionals in providing timely and accurate treatment.

## Approach
Transfer learning techniques were employed to build an artificial intelligence system capable of pneumonia detection. The system utilizes ResNet architectures and was implemented using Python and TensorFlow. Google Colab GPU and TensorBoard were utilized for efficient training and evaluation of the models.

## Key Technologies Used
- Python
- TensorFlow
- Google Colab GPU
- TensorBoard
- ResNet architectures

## The Dataset
The dataset used in this project is organized into three folders: train, test, and val. It consists of X-ray images (JPEG) categorized into two classes: Pneumonia and Normal. The dataset contains a total of 5,863 images.

Chest X-ray images (anterior-posterior) were obtained from pediatric patients between the ages of one to five years old. These images were sourced from the Guangzhou Women and Children’s Medical Center in Guangzhou. Prior to training the AI system, all chest radiographs underwent quality control screening to remove low-quality or unreadable scans. Expert physicians then graded the images for diagnosis, with a third expert reviewing the evaluation set to account for any grading errors.

The dataset used in this project is available on Kaggle: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Achievement
The developed system successfully distinguished between bacterial and viral pneumonia on chest X-ray images. It serves as a prototype for potential application in the field of biomedical imaging, providing a valuable tool for diagnosing pneumonia accurately and efficiently.

**Credit:** Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), "Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification", Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2
