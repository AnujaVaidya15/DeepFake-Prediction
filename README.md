# DeepFake-Prediction

# DeepFake-Prediction

**DeepFake-Prediction** is a deep learning project focused on detecting manipulated or AI-generated facial content. Leveraging transfer learning with **MobileNetV2**, this project classifies images as either real or deepfake using the `prithivMLmods/Deepfake-vs-Real` dataset from Hugging Face.

##  Overview

With the rise of synthetic media, detecting deepfakes has become increasingly important. This project builds a lightweight and efficient classifier suitable for real-time deployment, powered by MobileNetV2—a highly optimized neural network for mobile and embedded vision applications.

##  Dataset

- **Name**: [Deepfake-vs-Real](https://huggingface.co/datasets/prithivMLmods/Deepfake-vs-Real)
- **Source**: Hugging Face Datasets
- **Format**: Labeled images of real and fake faces
- **Usage**:
  ```python
  from datasets import load_dataset

  dataset = load_dataset("prithivMLmods/Deepfake-vs-Real")
