# Enhancing Road Safety with AI-Powered Accident Detection

## Objective
The objective of this project is to develop an AI-driven system that detects accident scenes from images captured by CCTV footage. By leveraging advanced machine learning techniques, we aim to improve response times to road incidents, thereby enhancing overall road safety.

## Data Sample
We utilized the [Accident Detection from CCTV Footage](https://www.kaggle.com/datasets/ckay16/accident-detection-from-cctv-footage/data) dataset from Kaggle. This dataset contains annotated images from CCTV footage, showcasing various accident scenarios.

### Sample Data
Here’s a sample from the dataset:

| Image | Label |
|-------|-------|
| ![Accident Image](path/to/sample_image.jpg) | Accident |

The images are categorized into "Accident" and "No Accident," which helps train the model to distinguish between accident scenes and normal traffic conditions.

## Model Architecture
Our model employs a Vision Transformer (ViT) architecture, which is well-suited for image classification tasks. The key components of the model include:
- **Input Layer:** Accepts images resized to a specified resolution.
- **Transformer Encoder Layers:** Extract features through self-attention mechanisms, capturing spatial relationships.
- **Feedforward Neural Networks:** Process the features and classify them into accident-related categories.
- **Output Layer:** Provides the final classification probabilities for "Accident" and "No Accident."

## Instructions for Running the Training Job
To run the training job, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/accident-detection.git
   cd accident-detection
