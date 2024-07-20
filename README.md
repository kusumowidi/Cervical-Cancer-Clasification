# Classification of Normal and Pathological Cervical Cells in Pap Smear Images Using the CNN Method
This is my final project for the "Biomedical Image Processing" course, focusing on classifying normal and pathological cervical cells in Pap smear images using CNN methods. The project employs Convolutional Neural Networks to analyze and distinguish between healthy and abnormal cervical cells effectively.

# Background
More than 90% of cervical cancers are caused by human papillomavirus (HPV) infection. Early detection is crucial, but cervical cancer remains a leading cause of death among women despite advances in screening and vaccination. The virus can damage squamous and glandular cells in the cervix, potentially leading to cancer. According to WHO, cervical cancer is the fourth most common cancer in women, with 530,000 new cases in 2012. The Pap smear test, a common screening method, detects abnormal cervical cells but has low sensitivity and specificity. Recently, computer algorithms, especially Convolutional Neural Networks (CNNs), have been developed to improve cervical cancer diagnosis through advanced image processing techniques.

# Methode
### The Dataset 
The dataset we used is "SIPAKMED: A New Dataset For Feature And Image Based Classification Of Normal And Pathological Cervical Cells In Pap Smear Images," sourced from Kaggle. This dataset is available for free and can be accessed online via the following link: [Cervical Cancer Largest Dataset (SipakMed)](https://www.kaggle.com/datasets/prahladmehandiratta/cervical-cancer-largest-dataset-sipakmed/data). The SIPaKMeD Database comprises 4,049 manually cropped images of isolated cells from 966 cell cluster images on Pap smear slides, which are also included in the dataset. These images were captured using a CCD camera (Infinity 1 Lumenera) mounted on an optical microscope (OLYMPUS BX53F).

Dataset Preview:

<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/Data.png"  width="70%" height="70%"/> 

# Model

| Model          | Number of Parameters | Model Structure |
|----------------|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Model 1 CNN** | 392.741           |<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model1.png"  width="40%" height="35%"/>            |
| **Model 2 CNN** | 915.909           |<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model2.png"  width="50%" height="50%"/>      |

# Result

|                       | Custom CNN           | ResNet50 |
|-----------------------|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Clasification Report**          |<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model1_CR.png"  width="80%" height="80%"/>| <img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model2_CR.png"  width="80%" height="80%"/>|
| **Model Loss**        |<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model1_Loss.png"  width="80%" height="80%"/>|<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model2_Loss.png" width="80%" height="80%"/>|
| **Confussion Matrix** |<img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model1_CF.png"  width="80%" height="80%"/>| <img src="https://github.com/kusumowidi/Cervical-Cancer-Clasification/blob/main/result/model2_CF.png"  width="80%" height="80%"/>|

