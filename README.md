# Movie Genre Classification

Welcome to the Movie Genre Classification project! This repository contains a Jupyter Notebook that demonstrates how to build a machine learning model to classify movies into various genres based on their plot summaries.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)

## Introduction
Movie genre classification is an important task in the field of Natural Language Processing (NLP). Accurate genre classification can help in better organizing and recommending movies to users. This project demonstrates how to use machine learning techniques to classify movie genres from their plot summaries.

## Project Structure
The repository is organized as follows:

## Installation
To run this project locally, please follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/longduongbao29/movie_genres_classification
    cd movie-genre-classification
    ```

2. Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. (Optional) Install Jupyter Notebook if not already installed:
    ```bash
    pip install notebook
    ```

## Usage
1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open the `ML_8_Combined_final.ipynb` notebook and follow the instructions to execute each cell. The notebook will guide you through:
    - Loading and preprocessing the dataset
    - Building and training the machine learning model
    - Evaluating the model's performance

## Dataset
The dataset used in this project includes movie plot summaries and their corresponding genres. It can be downloaded from https://drive.google.com/uc?id=1hUqu1mbFeTEfBvl-7fc56fHFfCSzIktD. Please download the dataset and place it in the `data/raw` directory before running the notebook.

## Model
The model used for classification is a neural network built using TensorFlow and Keras. The notebook provides a detailed walkthrough of the model architecture and training process. Feel free to modify the model parameters and architecture to experiment with different configurations.

## Results
The results of the model, including accuracy, precision, recall, and F1-score, are presented in the notebook. Visualizations such as confusion matrices and classification reports are also included to provide a comprehensive evaluation of the model's performance.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request. Ensure that your contributions align with the project's coding standards and guidelines.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
