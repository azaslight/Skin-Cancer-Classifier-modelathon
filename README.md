# Skin-Cancer-Classifier-modelathon

# Skin Cancer Classifier with Telegram Bot

This project implements a skin cancer classification model that uses machine learning to classify skin lesions based on images. The model is integrated with a Telegram bot that allows users to send skin lesion images for classification.

## Features
- **Model**: A deep learning model trained on the HAM10000 dataset to classify skin lesions into multiple categories.
- **Telegram Bot**: Allows users to interact with the model by sending images via Telegram. The bot classifies the image and provides the result along with the confidence score.
- **Image Preprocessing**: The uploaded image is preprocessed (resized and normalized) before being passed to the model for prediction.

## Requirements
To run this project, you need the following Python libraries:
- tensorflow==2.12.0
- numpy==1.23.5
- opencv-python==4.7.0.72
- matplotlib==3.7.1
- pyTelegramBotAPI==4.25.0
- pillow==9.4.0
- scikit-learn==1.2.1
- joblib==1.3.0

Install all dependencies by running:
pip install -r requirements.txt


## Setup
1. Clone this repository.
2. Install the required libraries using the command above.
3. Download the pre-trained model and label encoder file.
4. Run the Telegram bot by executing the `area51_telegram.ipynb` notebook.

## Usage
1. Start the Telegram bot by sending the `/start` command.
2. Send an image of a skin lesion to the bot.
3. The bot will classify the lesion and return the result along with the confidence score.

## Author
Seiten Azamat
