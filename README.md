# Iris Flower Classification

This repository contains a simple machine learning project for classifying Iris flowers based on their sepal and petal measurements.

## Features and Functionality

This project provides the following functionalities:

*   **Data Loading and Preprocessing:** Loads the Iris dataset and prepares it for model training.
*   **Model Training:** Trains a Support Vector Machine (SVM) model on the Iris dataset.
*   **Model Evaluation:** Evaluates the trained model's performance using accuracy and a confusion matrix.
*   **Prediction:** Allows for predicting the species of an Iris flower based on its sepal and petal measurements.
*   **Pickle Serialization:** Saves the trained model to a pickle file for later use.

## Technology Stack

*   **Python:** Programming language.
*   **scikit-learn (sklearn):** Machine learning library for model training and evaluation.
*   **pandas:** Data analysis and manipulation library.
*   **matplotlib:** Data visualization library.
*   **NumPy:** Numerical computing library.
*   **joblib:** Library for saving/loading the model
## Prerequisites

Before running this project, you need to have the following software installed:

*   **Python (3.6 or higher):** You can download Python from [https://www.python.org/downloads/](https://www.python.org/downloads/).
*   **pip:** Python package installer (usually included with Python).

You also need to install the required Python packages. You can install them using pip:

```bash
pip install scikit-learn pandas matplotlib numpy joblib
```

## Installation Instructions

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/NufalXBaalash/Irist_Flower_Classification.git
    cd Irist_Flower_Classification
    ```

2. **(Optional) Create a virtual environment:**
    It is recommended to create a virtual environment to isolate the project dependencies.

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```
3.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt #create and use requirements.txt if available
    ```

## Usage Guide

To run the classification project, execute the main script.

1.  **Run the script:**

    ```bash
    python main.py #or python your_script_name.py if you have the python file with name differnet from 'main'
    ```

    This script will:

    *   Load the Iris dataset.
    *   Split the data into training and testing sets.
    *   Train an SVM model.
    *   Evaluate the model's performance.
    *   Print the accuracy and confusion matrix.
    *   Save the trained model to a file named `iris_model.pkl` using joblib.

## Contributing Guidelines

Contributions to this project are welcome!  Here are the general guidelines:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Test your changes thoroughly.
5.  Submit a pull request to the `main` branch.

Please follow the existing code style and conventions.

## License Information

This project is licensed under the MIT License. See the `LICENSE` file for more information.

```
MIT License

Copyright (c) [Year] [Your Name or Organization]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contact/Support Information

If you have any questions or need support, please feel free to contact:

*   [NufalXBaalash](https://github.com/NufalXBaalash)

```
