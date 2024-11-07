Citrus Fruit Detection Using Deep Learning
Overview
This project demonstrates the implementation of a deep learning model using Google Colab and YOLOv9 for detecting and counting citrus fruits on trees. The model identifies citrus fruits in images and provides the total count of detected fruits. The goal is to achieve high accuracy in fruit detection, with results displayed on a web interface using Java for the frontend.

Installation
To set up and run the project locally, follow these steps:

Clone the YOLOv5 Repository (for YOLOv9 functionality):

Open Google Colab and clone the YOLOv5 repository:
python
Copy code
!git clone https://github.com/ultralytics/yolov5
Upload the YOLOv9 Dataset:

Ensure your dataset is available in Google Drive. Mount Google Drive in Colab:
python
Copy code
from google.colab import drive
drive.mount('/content/drive')
Navigate to your dataset folder in your drive and load it for training.
Install Required Dependencies:

Install the required dependencies in Colab:
python
Copy code
%pip install -U -r yolov5/requirements.txt
%pip install ultralytics
Configure and Train the Model:

Configure the dataset path and start training the model with YOLOv9.
Usage
Running the Model:
Execute the Colab notebook to train and evaluate the model on citrus fruit detection. You may adjust hyperparameters to optimize performance.
Viewing the Results:
The model’s predictions, including the fruit counts, will be displayed in the output section of the notebook.
Additionally, integrate the model output with a Java-based frontend web page to display the detection results and count.


