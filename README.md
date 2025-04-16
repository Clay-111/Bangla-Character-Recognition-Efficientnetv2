# Bangla Character Recognition with EfficientNetV2

This project implements a Bangla handwritten character recognition system using the EfficientNetV2 architecture. The model is trained to recognize Bangla characters and provides predictions for drawn characters.

## 📌 Features

- **EfficientNetV2**: Utilizes the EfficientNetV2 architecture for state-of-the-art performance.
- **Real-Time Drawing Recognition**: Draw a Bangla character on a canvas, and the model will predict the character in real-time.
- **PyTorch Framework**: Built using PyTorch for flexibility and ease of use.
- **Metrics**: Includes accuracy evaluation using `sklearn.metrics.accuracy_score`.
- **Visualization**: Uses `matplotlib` for visualizing results.
- **Dataset Handling**: Supports loading and transforming datasets using `torchvision.transforms` and `torch.utils.data.DataLoader`.

## 📁 Project Files

- [`Bangla_Handwritten_EfficientNetV2.ipynb`](./Bangla_Handwritten_EfficientNetV2.ipynb)  
  Jupyter Notebook for training, evaluation, and real-time recognition of Bangla handwritten characters.

- [**Bangla_Dataset.zip**](https://drive.google.com/file/d/150Yr_t5qTZdpc3fbN8YGWtII4oXt-RMU/view?usp=drive_link)  
  Dataset containing Bangla handwritten characters (hosted externally due to GitHub's file size limit).

## 🛠️ Code Highlights

### Libraries Used
The project uses the following libraries:

- **torch** and **torchvision**: For model building and dataset handling.
- **PIL**: For image processing.
- **sklearn.metrics**: For accuracy evaluation.
- **matplotlib**: For visualizing results.
- **pygame**: For creating a drawing canvas.

### Key Functionalities
- **Dataset Loading**: Uses `torchvision.datasets` and `torchvision.transforms` to load and preprocess the dataset.
- **Model Training**: Implements training loops with `torch.optim` and `torch.nn` for optimizing the model.
- **Drawing Canvas**: Uses `pygame` to create an interactive canvas for drawing Bangla characters.
- **Prediction**: Converts the drawn image into a format suitable for the model and predicts the character.

## 📊 Results
The model's performance is evaluated using accuracy metrics. Visualizations of the training process and predictions are included in the notebook.
