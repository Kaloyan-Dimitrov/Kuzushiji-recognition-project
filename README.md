# Kuzushiji Recognition Project
## Overview
The Kuzushiji Recognition Project is an initiative aimed at classifying handwritten characters in ancient Japanese manuscripts. This project leverages machine learning techniques to decipher the Kuzushiji script (くずし字), a cursive script used in Japan prior to the Meiji restoration in 1868. Despite the modernization of the Japanese language, hundreds of thousands of historical documents remain unreadable to most, as the Kuzushiji script is no longer taught in schools. Our goal is to make these documents accessible to a wider audience by automating the recognition of Kuzushiji characters.

## Motivation
Historical documents are windows into our past, offering insights into the culture, norms, and values of societies before our time. The Kuzushiji script, once widespread in Japan, encapsulates a significant part of Japanese heritage. Unfortunately, the modernization of the language has rendered these documents incomprehensible to the majority. Through this project, we aim to preserve and provide access to this valuable historical content.

## Dataset
The project utilizes a [dataset](https://www.kaggle.com/c/kuzushiji-recognition/overview) from a Kaggle competition focused on Kuzushiji recognition. This dataset includes images of pages from historical manuscripts, annotated with the locations and classifications of each character.

## Project Structure
- KuzushijiRecognitionProject.ipynb: The main Jupyter notebook containing data acquisition, preprocessing, model training, and evaluation steps.
- Data: Directory containing the dataset used for training and testing the model. Due to licensing, you will need to download the dataset directly from Kaggle.
- README.md: This document, providing an overview of the project.
## Getting Started
- Clone this repository to your local machine.
- Download the dataset from the Kaggle competition page and place it in the Data directory.
- Ensure you have Jupyter Notebook or JupyterLab installed, along with Python and the necessary libraries such as TensorFlow, Keras, NumPy, and Matplotlib.
- Open and run the KuzushijiRecognitionProject.ipynb notebook to start exploring the project.
##How to Contribute
Contributions to improve accuracy, efficiency, or usability are welcome. To contribute:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Submit a pull request with your changes.
## License
This project is open-sourced under the MIT License. See the LICENSE file for more details.
