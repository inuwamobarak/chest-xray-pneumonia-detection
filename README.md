# Pneumonia Detection using chest X-ray images

Pneumonia is an inflammatory condition of the lung primarily affecting the small air sacs known as alveoli. Symptoms typically include some combination of productive or dry cough, chest pain, fever, and difficulty breathing. The severity of the condition is variable.
Pneumonia. (2023, January 28). In Wikipedia. https://en.wikipedia.org/wiki/Pneumonia

![485px-Symptoms_of_pneumonia svg](https://user-images.githubusercontent.com/65142149/215302250-841fde71-e182-4ffd-8036-625a3a717de7.png)
 **Motivation:** To build an automated system to detect and classify human diseases(Pneumonia) from medical images.
## Approach
Used transfer learning techniques to develop an artificial intelligence system.
### Key Technologies used
* Python
* Tensorflow
* Google Colab GPU
* TensorBoard
* Resnet architectures
## The Dataset
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert. Source: Kaggle https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
**Achievement:** Accurately distinguished bacterial and viral pneumonia on chest X-rays and serves as a prototype for application in biomedical imaging.

**Credit:** Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification”, Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2
