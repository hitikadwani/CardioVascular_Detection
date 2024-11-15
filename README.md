# Cardiovascular Disease Detection Using Deep Learning and Machine Learning Models on ECG Images
## Group Members
HITIK ADWANI - 22BDS029  
LAKSHYA BABEL - 222BDS033  
ABHIJIT SINGH - 22BDS054  
SURYANSH AYUSH - 22BDS057

## Overview
This project implements a system for cardiovascular disease detection using ECG images. By leveraging advanced Machine Learning (ML) and Deep Learning (DL) techniques, including Convolutional Neural Networks (CNNs), the system automates early diagnosis and improves the accuracy of heart disease detection.


## Dataset

The dataset contains ECG images representing both normal and abnormal heart activities. It is sourced from [Mendeley](https://data.mendeley.com/datasets/gwbz3fsgp8/2).

## Methodology
1. Data Preprocessing:
Convert ECG images to grayscale.
Apply Gaussian filtering and thresholding.
Extract and trace individual leads.
2. Model Training:
Train ML and CNN models using preprocessed ECG images.
3. Evaluation:
Assess model performance using metrics like Accuracy, Precision, Recall, and F1-Score.

## Project Setup

To set up this project locally, follow these steps:  

### Step 1: Clone the Repository  


```bash
git clone https://github.com/hitikadwani/CardioVascular_Detection.git
```

### Step 2: Navigate to the Project Directory
```bash
cd CardioVascular_Detection 
``` 

### Step 3: Install Required Packages
```bash
pip install -r requirements.txt
```

### Step 4: Run Jupyter Notebooks
1. Open Jupyter Notebook:
2. In Jupyter Notebook, navigate to the notebooks folder.
3. Open and run Cardiovascular_Detection_DL.ipynb for the deep learning model or Cardiovascular_Detection_ML.ipynb for the machine learning model.



## Conclusion

This project demonstrates the potential of leveraging Machine Learning and Deep Learning models for early detection of cardiovascular diseases using ECG images. The proposed system achieved high accuracy across multiple models, with the CNN model demonstrating superior performance in both training (98% accuracy) and validation (92% accuracy). 

The system's automated approach offers a fast, reliable, and scalable solution for heart disease detection, reducing dependency on manual ECG interpretation. The study also highlights the importance of preprocessing techniques like grayscale conversion and signal extraction to improve model performance.

Future enhancements include extending the model to detect multiple heart conditions, further optimizing feature extraction, and improving overall accuracy. These advancements could make the system even more applicable in clinical settings, particularly for telemedicine and remote healthcare solutions.



## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to the [Cardiovascular_Detection repository](https://github.com/hitikadwani/CardioVascular_Detection.git).

## Links  

[Link to report](https://drive.google.com/file/d/1fbhN-4j4a9EZeFtVn4-A_sTueuMMswga/view?usp=drive_link)  
[Link to PPT](https://docs.google.com/presentation/d/1ajg00v7bxsgj3RrIOb4QwV1slYUbII_s/edit?usp=sharing&ouid=116995870568451359349&rtpof=true&sd=true)  
[Link to Video](https://drive.google.com/file/d/1ru4gVayziGQFJndI09Zoase68xKsT3wS/view)

