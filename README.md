# IIT_Dhanbad

## Problem Statement

The objective of this project is to perform the classification of individual rocks into three categories: big, medium, and small. Additionally, the project aims to predict the falling pattern of these rocks by analyzing the provided images of the rock dump.

## Environment Setup

This project is developed using Python 3.10. The required libraries and packages are listed below:

### Requirements

- **tensorflow_gpu==2.10**
- **opencv**
- **model hed for opencv**: You can find the model at [https://github.com/s9xie/hed](https://github.com/s9xie/hed)
- **scikit-learn**
- **matplotlib**

To set up the environment, you can use the following commands:

```bash
pip install tensorflow_gpu==2.10 opencv-python scikit-learn matplotlib
```
# Folder Structure
```bash
IIT_Dhanbad/
├── code/
│   ├── heD_model/
│   ├── segment_data/
│   ├── train/
│   |── model.ipynb
│   │── model2.ipynb
│   │── model3.ipynb
│   └── cook/
├── data/
│   ├── images/
│   ├── masks/
│   └── mask/
├── mask_prep/
├── train/
```


Here's a brief description of the folders in this project:

- **code/**: Contains various project-related code files.
  - **heD_model/**: HED model implementation or files related to it.
  - **segment_data/**: Semantically segmented individual rock data.
  - **train/**: Jupyter notebooks for training the models.
  - **cook/**: Temporary folder for other purposes
- **data/**: Holds the image and mask data for the project.
  - **images/**: Image data used for training and analysis.
  - **masks/**: Mask data with 0 and 255 values.
  - **mask/**: Mask data with actual mask values of 0 and 1.

- **mask_prep/**: Contains prepared masks.

- **train/**: Additional training-related data or files.

# Input data

![2](https://github.com/RajKrishna2123/IIT_Dhanbad/assets/58541488/3523f446-8cb0-4794-a1cf-95e8aa3b729c) ![2](https://github.com/RajKrishna2123/IIT_Dhanbad/assets/58541488/ba5933c0-5263-4f4b-8183-155b788bd922)

# result data

![selective_segment](https://github.com/RajKrishna2123/IIT_Dhanbad/assets/58541488/b631d2b5-3f62-4e56-8b67-43fb062efefa)

