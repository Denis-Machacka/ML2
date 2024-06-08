# Chess Piece Classifier

This repository contains a Google Colab notebook for classifying chess pieces using a deep learning model based on MobileNetV2. The model aims to accurately identify different types of chess pieces from images.

## Instructions

To use the notebook, follow these steps:

1. **Download the Notebook:**
   - Click on the `Chess_Piece_Classifier.ipynb` file.
   - Click on the "Download" button to save the notebook to your local machine.

2. **Run on Google Colab:**
   - Open [Google Colab](https://colab.research.google.com/).
   - Click on `File` > `Upload notebook`.
   - Choose the downloaded `Chess_Piece_Classifier.ipynb` file from your local machine.
   - Run the cells in the notebook sequentially to execute the code.

## Additional Information

- **Dependencies:**
  - The notebook uses TensorFlow and Keras for building and training the model. These libraries are pre-installed on Google Colab.
  - Ensure you have an active internet connection to access and run the notebook on Google Colab.

- **Model Training:**
  - The model is pre-trained on ImageNet and fine-tuned on a custom dataset of chess pieces.
  - Dropout and L2 regularization are used to prevent overfitting.

- **Dataset:**
  - The dataset consists of images of chess pieces, categorized into six classes.
  - The dataset should be uploaded to your Google Drive and connected to the Colab notebook as shown in the code.

## Troubleshooting and Support

If you encounter any issues or have questions about the notebook, please feel free to contact me at machaden@students.zhaw.ch.
