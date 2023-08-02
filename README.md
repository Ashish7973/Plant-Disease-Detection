****Plant Disease Detection********

This repository contains code for a plant disease detection project, specifically focusing on the detection of diseases in corn (maize) plant leaves. The project uses the PlantVillage dataset, which can be found on Kaggle [here]([url](https://www.kaggle.com/abdallahalidev/plantvillage-dataset)).


**Introduction**
Plant diseases can significantly affect crop yield and quality. Early detection of diseases is crucial for implementing timely and effective control measures. This project aims to build a machine learning model for the detection of diseases in corn plant leaves, using state-of-the-art techniques in computer vision and deep learning.

**Dataset**
The dataset used for this project is the PlantVillage dataset available on Kaggle. It contains a wide variety of plant images, including healthy and diseased samples. For this project, we primarily focus on four classes of corn plant leaves, namely [Common rust, northern leaf blight,  Cercospora, healthy leaves].

To use the dataset, you can download it from the Kaggle link provided above and place the images in the appropriate data folders before running the code.

**Installation**
1. Clone this repository to your local machine using git clone https://github.com/your-username/plant-disease-detection.git
2. Navigate to the project directory: cd plant-disease-detection
3. Install the required dependencies:
    a. If you prefer using Jupyter Notebook for interactive development, you can install the necessary dependencies by running the following command:

          pip install jupyterlab
     b. Alternatively, if you want to use a virtual environment for this project, you can create and activate a new environment before installing the dependencies:
   
          python -m venv env
          source env/bin/activate  # On Windows, use `env\Scripts\activate`
    c. Now, install the required packages using pip:
   
          pip install -r requirements.txt
    d. Once the dependencies are installed, you can launch the Jupyter Notebook:
   
          jupyter lab
5. This will open the Jupyter Lab interface in your default web browser, where you can access the project notebooks.

**Usage**
--> Make sure you have downloaded the PlantVillage dataset and organized the images of corn plant leaves in appropriate folders.

--> Modify the configuration file, if necessary, to adjust hyperparameters, data paths, or other settings for the model.

--> Run the main notebook in order chunks to train the model

**Contributing**
Contributions to this repository are always welcome. If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.

When contributing to this project, please follow the code of conduct and adhere to the coding standards for consistency.

We would appreciate it if you provide attribution to the original authors by linking back to this repository.
