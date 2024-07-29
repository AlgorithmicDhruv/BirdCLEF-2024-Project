# BirdCLEF 2024 Audio Classification Project

## Overview

This project focuses on bird species identification from audio recordings in the Western Ghats, India, using machine learning techniques. The goal is to contribute to efforts in protecting avian biodiversity.

## Project Structure

- **`birdclef_audio.ipynb`**: The Jupyter notebook containing the entire analysis and modeling process.

## Data

The dataset used in this project is from the [BirdCLEF 2024 competition](https://www.kaggle.com/competitions/birdclef-2024/data) on Kaggle. It includes:
- Training audio files
- Metadata for the training set
- Unlabeled test audio files

## Setup

As there is no script or `requirements.txt`, the notebook should be run in an environment where the following libraries are available:
- TensorFlow 2.15.0
- Keras 3.3.3
- KerasCV 0.9.0
- Other libraries: `numpy`, `pandas`, `librosa`, `matplotlib`, `tensorflow_io`, `tqdm`

## Instructions

1. **Download the Dataset**:
    Download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/birdclef-2024/data) and place it in the directory structure as specified in the notebook.

2. **Install Required Libraries**:
    Install the required libraries using pip:
    ```bash
    pip install tensorflow==2.15.0 keras==3.3.3 keras-cv==0.9.0 numpy pandas librosa matplotlib tensorflow-io tqdm

3. **Run the Notebook**:
    Open the `birdclef_audio.ipynb` notebook in Jupyter and run all cells to execute the code and see the results. 

## Results

The notebook trains a model using the `EfficientNetV2` architecture and generates predictions for the test dataset.
The predictions are saved in submission.csv.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- BirdCLEF 2024 for providing the dataset.
- TensorFlow and KerasCV for their powerful machine learning libraries.
