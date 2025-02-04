# Breast Cancer Classification using Deep Learning

## Overview
This project demonstrates **Breast Cancer Classification** using a deep learning model built with **TensorFlow and Keras**. The model is trained on the **Breast Cancer Wisconsin Dataset** and predicts whether a tumor is **Benign (1) or Malignant (0).**

## Features
- Loads the dataset from `sklearn.datasets`.
- Performs **data preprocessing** (handling missing values, standardization).
- Builds a **Neural Network** for classification.
- Trains the model using **Adam optimizer & sparse categorical crossentropy loss**.
- Evaluates the model using **accuracy & loss visualization plots**.
- Implements a **predictive system** to classify new data.

## Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/Breast_Cancer_Classification.git
cd Breast_Cancer_Classification
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook:
```bash
jupyter notebook Breast_Cancer_Classification.ipynb
```

## Dataset
The dataset used is the **Breast Cancer Wisconsin Dataset**, available in the `sklearn.datasets` module.

## Model Architecture
- **Input Layer:** Takes standardized feature data.
- **Hidden Layers:** Fully connected layers with ReLU activation.
- **Output Layer:** A softmax layer for binary classification.

## Results
### Accuracy & Loss Plots:
![Accuracy Plot](path/to/accuracy_plot.png)
![Loss Plot](path/to/loss_plot.png)

### Example Prediction:
| Features | Prediction |
|----------|------------|
| [15.3, 20.4, ...] | Malignant (0) |
| [12.1, 18.5, ...] | Benign (1) |

## Next Steps
- Apply **hyperparameter tuning** to improve accuracy.
- Deploy the model as a **Flask or FastAPI web app**.
- Convert the notebook into a **Python script for automation**.

## Contributing
Feel free to open an issue or submit a pull request if you find any improvements!

## License
This project is licensed under the MIT License.

