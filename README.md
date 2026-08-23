# Traffic Sign Detection System

A deep learning-based system that can accurately detect and classify traffic signs using Convolutional Neural Networks (CNNs). This project is implemented using Keras and TensorFlow, providing both a trained model and a user-friendly GUI interface for real-time traffic sign classification.

## Live Demo
🔗 [Try the live demo here](https://ayus1234.github.io/Traffic_Sign_Detection_System/)

## Features

- Traffic sign classification using CNN architecture
- Interactive GUI interface for easy usage
- Support for multiple traffic sign categories
- Pre-trained model included
- High accuracy in classification

## Project Structure

- `GUI.ipynb`: Interactive GUI implementation for the system
- `traffic_signs.ipynb`: Main notebook containing model training and evaluation
- `traffic_classifier.h5/.keras`: Trained model files
- `Train.csv`, `Test.csv`: Dataset files for training and testing
- `Meta.csv`: Metadata information
- `data/`: Directory containing dataset images

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Jupyter Notebook

## Installation

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install tensorflow keras numpy pandas opencv-python matplotlib jupyter
   ```
3. Launch Jupyter Notebook to run the GUI:
   ```bash
   jupyter notebook GUI.ipynb
   ```

## Usage

1. Open `GUI.ipynb` in Jupyter Notebook
2. Run all cells to start the GUI interface
3. Upload an image of a traffic sign through the interface
4. The system will process the image and display the predicted traffic sign class

## Model Information

The system uses a Convolutional Neural Network (CNN) architecture trained on a comprehensive dataset of traffic signs. The model achieves high accuracy in classifying various traffic sign categories.

## Screenshots

## Screenshot 1
![Screenshot (312)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/db779b23-5a8f-4c40-9964-20b2cbcc22d2)

## Screenshot 2
![Screenshot 2024-03-30 003120](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/fc944e83-f7c8-41e7-ae90-e380e4e5f12d)

## Screenshot 3
![Screenshot 2024-03-30 003211](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/9f7d4c5f-7df4-49aa-b08f-2b8ec7e411d6)

## Screenshot 4
![Screenshot (309)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/6305f186-944c-47e6-907c-58a30b2623e2)

## Screenshot 5
![Screenshot (310)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/d66c2b6c-fefb-4b5f-bf70-5096424e111d)

## Screenshot 6
![Screenshot (311)](https://github.com/ayus1234/Traffic_Sign_Detection_System/assets/107507481/8a70bee6-24f2-404b-861a-9235846f7db5)

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project.

## License

This project is open source and available under the MIT License.
