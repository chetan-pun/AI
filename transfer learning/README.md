
# Cat vs Dog Classification with VGG16

This project involves training an image classification model to differentiate between cats and dogs using the VGG16 architecture. The approach includes both feature extraction and fine-tuning of the VGG16 model to achieve high accuracy in classification.

## Project Overview

The goal of this project is to build and train an image classification model capable of distinguishing between images of cats and dogs. The VGG16 model, known for its deep architecture and performance, is utilized for this purpose. The project demonstrates the application of both feature extraction and fine-tuning techniques to improve model performance.

## Table of Contents

- [Installation](#installation)
- [Dataset](#dataset)
- [Training](#training)
- [Results](#results)

## Installation

To set up the project, you need to have Python installed along with the required libraries. You can install the necessary libraries using `pip`:

```bash
pip install tensorflow numpy matplotlib
```
## Dataset

The dataset used for this project is the [Dogs vs. Cats dataset](https://www.kaggle.com/c/dogs-vs-cats) from Kaggle. 

### Dataset Details
- **Source**: [Kaggle Dogs vs. Cats dataset](https://www.kaggle.com/c/dogs-vs-cats)
- **Categories**: 
  - Cats
  - Dogs
- **Structure**:
  - `dataset/`
    - `train/`
      - `cats/` (contains images of cats)
      - `dogs/` (contains images of dogs)
    - `validation/`
      - `cats/` (contains images of cats for validation)
      - `dogs/` (contains images of dogs for validation)
  
### Download Instructions
1. Go to the [Dogs vs. Cats competition page](https://www.kaggle.com/c/dogs-vs-cats) on Kaggle.
2. Download the dataset files.
3. Extract the files and organize them into the directory structure as shown above.

## Results

The model's performance was evaluated using accuracy metrics for both feature extraction and fine-tuning approaches. Below are the results:

### Feature Extraction
- **Training Accuracy**: 90%
- **Validation Accuracy**: 90%

### Fine-Tuning
- **Training Accuracy**: 92%
- **Validation Accuracy**: 92%

These results indicate that fine-tuning the VGG16 model provided a significant improvement in classification accuracy compared to using feature extraction alone.
