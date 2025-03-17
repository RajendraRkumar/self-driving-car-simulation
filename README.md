
# Self-Driving Car Steering Control

This project implements a model to predict the steering angle of a self-driving car. It is designed to work with the Udacity self-driving car simulator. The implementation uses Python and is executed within a specific Conda environment named `car`.

## Overview
A project to train a model for steering a car autonomously using computer vision techniques.

This project involves training a self-driving car model using Python and machine learning techniques. The model uses image processing to predict steering angles and navigate autonomously.

## Features
- Predicts steering angles based on input from the Udacity simulator.
- Model training and evaluation are conducted using Jupyter Notebook (`self_driving.ipynb`).
- Real-time driving control is handled by the `drive.py` script.
- Works seamlessly in a dedicated Conda environment for isolation.

---

## Prerequisites

### 1. Install Conda
Ensure Conda is installed on your system. If not, download and install it from the [official website](https://docs.conda.io/projects/conda/en/latest/user-guide/install/).

### 2. Udacity Simulator
Download and install the Udacity self-driving car simulator from [here](https://github.com/udacity/self-driving-car-sim). The simulator will be used to test the model.

---

## Environment Setup

1. Create and activate the Conda environment:
    ```bash
    conda create --name car python=3.8 -y
    conda activate car
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Verify the environment:
    ```bash
    conda list
    ```
---

## File Descriptions

### `self_driving.ipynb`
- Jupyter Notebook for training and evaluating the steering angle prediction model.
- Contains code for data preprocessing, model architecture, training, and validation.

### `drive.py`
- Script to connect the trained model to the Udacity simulator.
- Handles real-time steering predictions based on simulator input.

---

## Usage

### 1. Train the Model
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook self_driving.ipynb
    ```
2. Follow the steps in the notebook to train and evaluate the model.

### 2. Test the Model in the Simulator
1. Launch the Udacity simulator and select the autonomous mode.
2. Run the `drive.py` script to connect the model to the simulator:
    ```bash
    python drive.py
    ```

### 3. Switch Between Environments
activate the `car` environment before running any scripts:
```bash
conda activate car
```

---

## Notes
- The current implementation only predicts the **steering angle**. Further enhancements can include acceleration, braking, and lane detection.
- Ensure the simulator is running and properly configured before starting `drive.py`.


## Results
- The trained model achieves autonomous steering predictions based on real-time camera inputs.

---

## Acknowledgments
- Inspiration and guidance from Udacity.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Feedback
Feel free to open issues or submit pull requests for improvements. For any questions, contact kumrajenn@gmail.com.
