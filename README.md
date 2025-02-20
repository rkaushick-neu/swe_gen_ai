# Software Engineering & Generative AI
This repository is for the CSYE 7230: Software Engineering &amp; Generative AI course.

## Assignments
1. **Deep Learning models on Fashion MNIST dataset** ([README](#assignment-1-deep-learning-models-on-fashion-mnist-dataset) | Report | [Code](./Deep%20Learning%20MNIST/Rish_Analysis.ipynb))
2. **Generative Models on the CIFAR-10 dataset** ([README](#assignment-2-generative-models-on-the-cifar-10-dataset) | Report | Code)

## Assignment 1: Deep Learning models on Fashion MNIST dataset
### Dataset
The dataset has been obtained from [Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist/data)

### Visualizing Fashion Images
![First 25 images from the training dataset](./Deep%20Learning%20MNIST/visuals/visualizing_clothes.png)

### Baseline CNN Model 
#### Baseline CNN: Training & Loss Graph
![Baseline accuracy & loss](./Deep%20Learning%20MNIST/visuals/Training_Accuracy_And_Loss.png)

#### Baseline CNN: Correct Predictions
![Baseline Model: Correct Predictions](./Deep%20Learning%20MNIST/visuals/Correct_Predictions.png)

#### Baseline CNN: Incorrect Predictions
![Baseline Model: Incorrect Predictions](./Deep%20Learning%20MNIST/visuals/Incorrect_Predictions.png)

### CNN Model #2
#### CNN Model #2: Training & Loss Graph
![CNN model 2 accuracy & loss](./Deep%20Learning%20MNIST/visuals/CNN2_Training_Accuracy_And_Loss.png)

#### CNN Model #2: Correct Predictions
![CNN model 2: Correct Predictions](./Deep%20Learning%20MNIST/visuals/CNN2_Correct_Predictions.png)

#### CNN Model #2: Incorrect Predictions
![CNN model 2: Incorrect Predictions](./Deep%20Learning%20MNIST/visuals/CNN2_Incorrect_Predictions.png)

### Overall Performance Metrics

| Metric                  | Baseline CNN Model| CNN Model 2      | Improvement |
|-------------------------|-------------------|------------------|-------------|
| **Training Accuracy**   | 90.82%            | 99.54%           | **+8.72%**   |
| **Training Loss**       | 0.2607            | 0.0171           | -0.2436      |
| **Validation Accuracy** | 89.42%            | 94.41%           | **+5.00%**   |
| **Validation Loss**     | 0.2952            | 0.1990           | -0.0962      |
| **Testing Accuracy**    | 89.84%            | 94.24%           | **+4.40%**   |
| **Testing Loss**        | 0.2901            | 0.2148           | -0.0753      |

### Key Insights:
- **CNN Model 2** outperforms the **Baseline CNN Model** across all metrics, particularly in **accuracy** and **loss reduction**.
- Notable class-specific improvements in **T-shirt/Top**, **Pullover**, and **Shirt**, where the F1-scores increased significantly.
- Slight overfitting in CNN Model 2, but its robust test performance demonstrates strong generalization.

### Conclusion

In conclusion, CNN Model 2 significantly outperforms the Baseline CNN Model, achieving higher accuracy, lower loss, and improved class-wise metrics, particularly in challenging categories. While it shows slight overfitting, its robust test performance demonstrates superior generalization and optimization.

## Assignment 2: Generative Models on the CIFAR-10 dataset
### Dataset
I used the CIFAR-10 dataset which was created by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton, to work on this image generation project. 

### Visualizing CIFAR-10 Dataset
![Images from CIFAR-10](./Image%20Generation%20CIFAR-10/visuals/cifar10_classes_images.png)

![64 Images from CIFAR-10](./Image%20Generation%20CIFAR-10/visuals/cifar10_64_images.png)
