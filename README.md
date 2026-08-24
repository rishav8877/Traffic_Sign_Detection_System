# Traffic Sign Detection System

A deep learning-based **Traffic Sign Detection and Classification System** built using **Python, TensorFlow, Keras, and Convolutional Neural Networks (CNN)**. The system can identify and classify traffic signs from uploaded images and provides a simple GUI for easy interaction.

---

##  Project Overview

Traffic signs play an important role in road safety and intelligent transportation systems. This project uses a **Convolutional Neural Network (CNN)** to automatically recognize traffic signs from images.

The model is trained to classify **43 different traffic sign categories**. A Tkinter-based GUI is also provided where users can upload an image and get the predicted traffic sign.

---


## Features

* Classification of **43 traffic sign categories**
* CNN-based deep learning model
* Image upload functionality
* Simple graphical user interface using Tkinter
* Fast traffic sign prediction
* Training and validation accuracy visualization
* Pre-trained model included
* Jupyter notebooks for training and GUI implementation

---

## Technologies Used

* **Python**
* **TensorFlow**
* **Keras**
* **NumPy**
* **Pandas**
* **OpenCV / PIL**
* **Matplotlib**
* **Scikit-learn**
* **Tkinter**
* **Jupyter Notebook**

---
  

## Machine Learning Model

The project uses a **Convolutional Neural Network (CNN)** for image classification.

---

### Model Architecture

The CNN consists of:

* Convolutional layers
* ReLU activation functions
* Max Pooling layers
* Dropout layers
* Flatten layer
* Fully Connected Dense layer
* Softmax output layer

The input images are resized to **30 × 30 pixels** with 3 RGB channels.

The final layer contains **43 output classes**, representing the different traffic sign categories.

---


### Training Configuration

* **Input Size:** 30 × 30 × 3
* **Number of Classes:** 43
* **Optimizer:** Adam
* **Loss Function:** Categorical Cross-Entropy
* **Batch Size:** 32
* **Epochs:** 15
* **Activation:** ReLU and Softmax
* **Train/Test Split:** 80/20

---


## Traffic Sign Categories

The model can recognize traffic signs such as:

* Speed Limit signs
* No Passing
* Right-of-Way
* Priority Road
* Yield
* Stop
* No Entry
* General Caution
* Dangerous Curve
* Road Work
* Traffic Signals
* Pedestrian Crossing
* Children Crossing
* Bicycle Crossing
* Slippery Road
* Keep Left / Keep Right
* Roundabout Mandatory
* End of Speed Limit
* And many more

---


## 📂 Project Structure

```text
Traffic_Sign_Detection_System/
│
├── data/
│   └── dictionary.sqlite
│
├── GUI.ipynb
├── traffic_signs.ipynb
│
├── Train.csv
├── Test.csv
├── Meta.csv
│
├── traffic_classifier.h5
├── traffic_classifier.keras
├── my_model.h5
│
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Traffic_Sign_Detection_System.git
```

### 2. Navigate to the Project Directory

```bash
cd Traffic_Sign_Detection_System
```

### 3. Install Required Libraries

```bash
pip install tensorflow keras numpy pandas pillow matplotlib scikit-learn opencv-python jupyter
```

---


## Running the Project

### Option 1: Run the GUI

Open the GUI notebook:

```bash
jupyter notebook GUI.ipynb
```

Run all the cells and use the GUI to upload a traffic sign image.

The system will:

1. Open the image upload dialog.
2. Load the selected traffic sign image.
3. Resize the image to 30 × 30 pixels.
4. Pass the image to the trained CNN model.
5. Predict the traffic sign class.
6. Display the predicted traffic sign.

### Option 2: Train the Model

To train the model from scratch, open:

```bash
jupyter notebook traffic_signs.ipynb
```

The notebook loads the training data, preprocesses the images, creates the CNN model, trains it for 15 epochs, evaluates the model, and saves the trained model.

---


## Model Training

The training notebook performs the following steps:

```text
Dataset
   ↓
Image Loading
   ↓
Image Resizing (30 × 30)
   ↓
Data Preprocessing
   ↓
Train/Test Split
   ↓
One-Hot Encoding
   ↓
CNN Model Creation
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Trained Model
```

---

## GUI Workflow

```text
Upload Traffic Sign Image
          ↓
      Preprocessing
          ↓
    CNN Model Prediction
          ↓
    Predicted Class
          ↓
 Display Traffic Sign Name
```

---


##  Example

The following screenshots demonstrate the model training process, performance visualization, and the final traffic sign classification GUI.

### CNN Model Training Progress
   
![Screenshot (312)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/db779b23-5a8f-4c40-9964-20b2cbcc22d2)

*Jupyter Notebook output showing the CNN model training across multiple epochs with training and validation loss and accuracy metrics.*

---

### Training vs. Validation Accuracy
   
![Screenshot 2024-03-30 003120](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/fc944e83-f7c8-41e7-ae90-e380e4e5f12d)

*Accuracy curve comparing the model's training accuracy with validation accuracy across the training epochs.*

---

### Training vs. Validation Loss
   
![Screenshot 2024-03-30 003211](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/9f7d4c5f-7df4-49aa-b08f-2b8ec7e411d6)

*Loss curve showing the change in training and validation loss during CNN model training.*

---

### Traffic Sign Classification — Yield
   
![Screenshot (309)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/6305f186-944c-47e6-907c-58a30b2623e2)

*GUI prediction example where the trained CNN correctly identifies the uploaded traffic sign as Yield.*

---

### Traffic Sign Classification — Road Work
   
![Screenshot (310)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/d66c2b6c-fefb-4b5f-bf70-5096424e111d)

*GUI prediction example demonstrating recognition of a Road Work warning sign from the uploaded image.*

---

### Traffic Sign Classification — Speed Limit
   
![Screenshot (311)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/8a70bee6-24f2-404b-861a-9235846f7db5)

*GUI prediction example where the system identifies the uploaded sign as Speed Limit (30 km/h).*

---

## Applications

This project can be used as a foundation for:

* Advanced Driver Assistance Systems (ADAS)
* Autonomous vehicles
* Intelligent transportation systems
* Road safety applications
* Computer vision projects
* AI-based traffic monitoring systems
* Machine learning and deep learning education

---

## Future Improvements

Possible improvements include:

* Real-time traffic sign detection using a webcam
* Object detection instead of image classification
* Integration with OpenCV
* Deployment as a web application
* Mobile application integration
* Improved CNN architecture
* Data augmentation for better generalization
* Real-time video traffic sign recognition
* Deployment using TensorFlow Lite

---


## Dataset

The project uses a traffic sign dataset containing multiple categories of road signs. The dataset is divided into training and testing information and contains images representing **43 traffic sign classes**

---


## Contributing

Contributions are welcome!

If you would like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Create a Pull Request.

### Project Repository

Add your GitHub repository link here:

```text
https://github.com/your-username/Traffic_Sign_Detection_System
```
---

## License

This project is intended for educational and research purposes. You may modify and extend it according to your requirements.
