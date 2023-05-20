<h1 style='font-size:50px; text-align:center;font-weight:900;'>Melanoma vs Normal Moles</h1>

![melanoma](https://miiskin.com/wp-content/uploads/2019/09/how-melanoma-looks-like.jpg)

# Introduction

- Biomedical image processing has experienced dramatic growth and is an interdisciplinary research field attracting expertise from applied mathematics, computer science, engineering, statistics, physics, biology, and medicine.
- Computer-aided diagnostic processing has already become an important part of the clinical routine.
- Along with the onslaught of new high-tech developments and the use of different imaging modalities, additional challenges arise; for example, how to process and analyze large amounts of images to obtain high-quality information for disease diagnosis and treatment.
- The main objective of this project is to provide an efficient way to diagonize between the melanoma moles and the normal moles.
- This model is build on the VGG 16 architecture which contains sixteen layers which extracts the useful features from the image and thereby processes it.

# Objective

- To train CNN model which is capable of diagnosing melanoma vs non-melanoma cells.
- To improve the accuracy by using transfer learning technique.

# Reason for the project

**Melanoma is a type of skin cancer that can be life-threatening if left untreated. It is essential to diagnose melanoma early to increase the chances of successful treatment and a positive outcome. Melanoma diagnosis is necessary because:**

- **Early Detection:** Early detection of melanoma increases the chances of successful treatment. If diagnosed early, melanoma can often be removed through surgery or other treatments with a high success rate.

- **Prognosis:** The stage of melanoma at the time of diagnosis is a significant factor in determining the prognosis or the likely course of the disease. The earlier the diagnosis, the more favorable the prognosis.

- **Treatment Planning:** The diagnosis of melanoma helps medical professionals to determine the appropriate treatment plan for the patient. Treatment options may include surgery, radiation therapy, chemotherapy, immunotherapy, or a combination of these.

- **Monitoring:** Even after successful treatment, patients with melanoma require ongoing monitoring to detect any recurrence or spread of the disease. Regular check-ups and monitoring are necessary to ensure that the patient remains cancer-free and to detect any signs of a recurrence or spread of the disease.

In summary, the timely diagnosis of melanoma is crucial for the successful treatment and management of the disease. It is important to be aware of any changes in the skin, such as the appearance of new moles or changes in the size, shape, or color of existing moles, and to seek medical attention promptly if any concerns arise.

# Libraries required to run this notebook

- tensorflow
- keras
- sklearn
- matplotlib
- seaborn
- PIL
- pandas
- numpy
- cv2
- random
- os

## Follow the command to install the above libraries

#### tensorflow

- pip install tensorflow

#### keras

- pip install keras

#### sklearn

- pip install scikit-learn

#### PIL

- pip install Pillow

#### pandas

- pip install pandas

#### numpy

- Numpu will come along with tensorflow if it doesn't install try checking the below command line to install numpy
- pip install numpy

#### cv2

- pip install opencv-python

#### random

- This will come along with the python if not follow the steps
- pip install random2

#### os

- pip install os

# Summary

- The model gives **90% accuracy and 87% precision** in the **training data.**
- In the **testing data** the model gives **90% of accuracy and 88+ % precision.**
- In the **validation data** the model gives **91% of accuracy and 89+ % precision.**

### Prediction count on the test dataset

- The dataset contains **1781 melanoma** images and **1780 non melanoma** images.
- Among that it predicted **1548 melanoma** and **1650 non melanoma** were **correctly.**
- the images of count **233 melanoma** and **120 non melanoma** were predicted **wrongly.**

### Prediction count on the validation data dataset

- The dataset contains **1781 melanoma** and **non melanoma** images.
- Among that it predicted **1580 melanoma** and **1669 non melanoma** were **correctly.**
- the images of count **201 melanoma** and **112 non melanoma** were predicted **wrongly.**
