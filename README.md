# Transfer Learning Project in Python

This project demonstrates the application of **Transfer Learning** using a Deep Learning model in Python, implemented in Google Colab. The model is trained to classify images into two categories using the **Images Dataset** from Kaggle( or any custom dataset of your choice).

---

## Project Description

### Objective:
To implement Transfer Learning to train a model on a specific dataset efficiently by leveraging a pre-trained neural network. The project uses TensorFlow and Keras for model implementation.

### Framework:
- TensorFlow and Keras are used to implement the Transfer Learning approach.

---

## How to Use

### Prerequisites:
- Python 3.7+
- TensorFlow 2.x
- Google Colab (optional but recommended for GPU acceleration)

### Steps to Run the Project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/araujobma/Project1-DIO-TransferLearning.git
   ```

2. **Download the Dataset**:
   - Download the [Images Dataset from Kaggle](https://www.kaggle.com/datasets/pavansanagapati/images-dataset).
   - Alternatively, use a custom dataset by organizing images into folders (one per class).

--

## Key Features

- **Transfer Learning**:
  Utilizes a pre-trained network (e.g., VGG16, ResNet) to reduce training time and improve performance.

- **Customizable Dataset**:
  Easily replace the dataset with any other dataset of your choice.

- **Efficient Training**:
  Leverages Google Colab for free GPU acceleration to train the model faster.

---

## Results
- The final model achieves high accuracy in classifying the dataset into 7 categories.
- Transfer Learning significantly reduces the time required for training compared to training a model from scratch.

---

## Project Structure
```
|-- data/                 # Dataset folder
|-- notebook.ipynb        # Colab notebook with the Transfer Learning implementation
|-- README.md             # Project documentation
```

---

## References
- [Tensorflow Load Images Tutorial](https://www.tensorflow.org/tutorials/load_data/images)
- [Transfer Learning Guide](https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb)

---



---

## License
This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

