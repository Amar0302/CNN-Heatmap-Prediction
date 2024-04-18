# CNN Heatmap-Based Player Position Prediction

This repository contains a set of Python Jupyter notebooks dedicated to the scraping of football player heatmap and position data, and the development of a Convolutional Neural Network (CNN) model to predict player positions based on their heatmaps. The project focuses on data from Europe's top 5 leagues: England, Italy, Spain, France, and Germany, and extends its analysis to include unseen data from the Netherlands' top league for model validation.

## Overview

The project is structured into three main Jupyter notebooks:

1. **Sofascore Heatmap Scraping:** This notebook contains scripts to scrape player heatmap data from Sofascore for the top 5 European leagues. The data collected provides a spatial representation of player activities on the field, which is pivotal for understanding their playing positions and roles.

2. **Position Data Scraping:** This notebook focuses on scraping player position data, which is stored in a `.txt` file. Over 2400 players' positions are collected, offering a comprehensive dataset to label the heatmaps.

3. **Player Position Prediction CNN:** The third notebook develops a CNN model designed to predict player positions based on their heatmaps. The model is trained on the scraped data and tested on unseen data from the PSV (Netherlands) team to evaluate its performance.

## Objectives

- To collect and curate a dataset of player heatmaps and positions from the top European football leagues.
- To develop a CNN model that accurately predicts player positions from their heatmap data.
- To test the model's generalisability on unseen data from outside the initial dataset.

## Installation and Usage

To run these notebooks and utilise the scripts within your environment, follow these steps:

1. Clone this repository to your local machine or Jupyter environment.

`git clone https://github.com/Amar0302/CNN-Heatmap-Prediction`

2. Ensure you have Jupyter Notebook or JupyterLab installed. If not, you can install it using pip:

`pip install notebook`

3. Install all required Python dependencies listed in the `requirements.txt` file.

`pip install -r requirements.txt`

4. Open the notebooks in Jupyter and execute the cells sequentially to scrape data, train the model, and test the predictions.

## Dependencies

- BeautifulSoup for web scraping.
- TensorFlow and Keras for CNN model development.
- Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for data visualisation.

A complete list of dependencies can be found in the `requirements.txt` file.

## Dataset

The dataset created by the scraping notebooks includes:

- Heatmap data for players in the top 5 European leagues.
- Position data for players in the top 5 European leagues.

This dataset is crucial for training the CNN model and is available for further research and development.

## Model Development

The CNN model is developed using TensorFlow and Keras, with a focus on optimising for accuracy in predicting player positions. The model's architecture, training process, and validation are detailed within the Player Position Prediction CNN notebook.

## Testing and Validation

The model is tested on unseen data from the Netherlands' top league to assess its generalisability and performance in real-world scenarios.

## Contribution

Contributions to this project are welcome. Whether it's improving the model's accuracy, expanding the dataset, or refining the scraping scripts, please feel free to fork the repository and submit your pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Sofascore for providing the data used to train and test the model.
- The TensorFlow and Keras teams for their fantastic work on libraries that facilitate deep learning projects.
