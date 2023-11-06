
![145776554-d2d61b46-f9ca-4f91-a75e-ed2dafe7170d](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/8dcc7ebb-bd2e-429f-987e-e7acedf422b9)


# DisasterVision Classification: AI for Earthquake Impact Analysis

## Overview

DisasterVision Classification is a cutting-edge deep learning framework developed to categorize the degree of damage to buildings from satellite imagery following earthquakes. Utilizing the sophisticated U-Net convolutional neural network architecture, this tool distinguishes various levels of structural damage, assigning color codes for clear visual interpretation.

## Key Features

- Automated classification of building damage post-earthquake.
- Advanced image segmentation capabilities using the U-Net model.
- Data augmentation for improved model robustness.
- Evaluation metrics including IoU, Precision, and Recall for performance assessment.

## Getting Started

### Prerequisites

Ensure you have the following requirements installed:

- Python 3.x
- Keras, TensorFlow
- Numpy, OpenCV
- Matplotlib
- Scikit-learn

### Installation

To set up the project environment:

1. Clone the repository: //github.com/sneha1012/DisasterVision-Classification.git
2. Navigate to the project directory: cd DisasterVision-Classification
3.  Install the required dependencies: pip install -r requirements.txt


### Usage

Follow these steps to prepare your dataset and train the model:

1. Place your image files in `Images/` and label files in `Labels/`.
2. Run `augment.py` to augment the data: python3 augment.py
3. Execute `mask.py` to generate masks for training: python3 mask.py


4. Open and run the Jupyter notebook `Proposed_model.ipynb` to train the model.


![145777282-f9d16fd6-6abb-420a-9f55-61ae038cdf4e](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/0442aab9-fb95-4a64-8373-d705313631d0)

![147949934-6f3b0e33-13b8-4a25-a6b8-926389b837ff](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/1859a48e-5cd2-41a6-aba5-fe0060122ffb)

5. After training, use the model to classify new images and view the results.


![146252435-cf5904d0-e76d-4d93-aeca-b5f590d31769](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/7dcb9eae-9511-4724-9957-710e2de4c2d8)
![147950518-d6b03f7a-56e2-41f2-9032-e39e9f45f20c](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/0b1b519d-8fd1-4167-9a6f-c7e6614f8941)


## Model Architecture

Our U-Net architecture is tailored for precise image segmentation tasks, which is critical for accurate damage assessment in post-disaster scenarios.

![145995165-ee2b07b5-55d1-406b-92cd-6786dfefa05e](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/f422d238-365a-437b-91ae-1291841b5503)


## Results

The trained model achieves a high degree of accuracy, with performance metrics to back its reliability. Below are some of the classified images depicting the model's accuracy.

![Output_1-2](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/f20152c9-9d71-4827-8243-2dba2df85b29)![Output_9-2](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/9fea6e00-b816-453f-8abd-d1d937dc13aa)

![Output_12](https://github.com/sneha1012/DisasterVision-Classifier/assets/79008130/2e521052-13fd-41ca-8da2-86e65f18bf3d)






