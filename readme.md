
# Recommender Systems class
## Project 2

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2021

Author: Piotr Popowski

## About the project
The purpose of the project is to code a recommender based on a neural network model, tune it and evaluate it. The recommender recommends hotel rooms for users based on features created in previous project and compare the results with <b>AmazonRecommender</b>, <b>NetflixRecommender</b>. The project uses <b>keras</b> library with <b>adam</b> optimizer to initialize and train the neural network.

#### The project constists of two Jupyter notebooks:  
-   project_1_data_preparation.ipynb - notebook with data preparation from previous project,
-   project_2_recommender_and_evaluation.ipynb - the main notebook,
#### data preprocessing code:  
-   data_preprocessing/data_preprocessing_toolkit.py,
-   data_preprocessing/dataset_specification.py.py,
-   data_preprocessing/people_identifier.py.py
#### and data:  
-   data/hotel_data/hotel_data_original.csv.

#### All libraries used in project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- IPython.display
- torch
- math
- livelossplot
- keras
- random