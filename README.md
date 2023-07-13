# Fruit Recognition

This repository contains code for a fruit recognition task using a ResNet-18 model. The goal is to classify various fruits and vegetables based on their images.

![Fruits Image](https://images.unsplash.com/photo-1619566636858-adf3ef46400b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8N3x8ZnJ1aXRzfGVufDB8fDB8fHwy&auto=format&fit=crop&w=500&q=60)

## Dataset

The dataset used for this task consists of a collection of fruit and vegetable images. The dataset contains a total of 33 classes, including oranges, tomatoes, passion fruits, cucumbers, and more. The images are of size 100x100 pixels.

- Total number of images: 22,495
- Training set size: 16,854 images
- Test set size: 5,641 images

## Folder Structure

The folder structure of the project is as follows:
.
├── Data # Folder for storing local data
│ └── train.zip
├── LICENSE # License file
├── README.md # Documentation file
├── fruit-prediction-cnn.ipynb # Jupyter Notebook with the code
└── requirements.txt # File listing the dependencies

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/fruit-recognition.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Download the dataset and place it in the appropriate directory (`/kaggle/input/fruit-recognition/train/train`) as mentioned in the code.
4. Run the code: `python fruit_recognition.py`

## Code Structure

- `fruit_recognition.py`: The main Python script that performs data preprocessing, model training, and evaluation.
- `model.pkl`: The trained model saved in a pickle file.
- `README.md`: The documentation file providing an overview of the project.

## Dependencies

The code requires the following dependencies:

- Python 3
- NumPy
- pandas
- torch
- torchvision
- matplotlib
- seaborn
- scikit-learn
- zipfile

You can install the required dependencies using the command `pip install -r requirements.txt`.

## Results

The training process involves several epochs, and the model's performance is evaluated using the test set. The training and testing accuracies are plotted to track the model's performance over time. Additionally, a confusion matrix is generated to visualize the classification results.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
