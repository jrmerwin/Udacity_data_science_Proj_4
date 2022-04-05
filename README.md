# Udacity_data_science_Proj_4
### Udacity Data Science Nanodegree Capstone Project: Bitcoin Daily High Prediction
<br>
Required Installations
<ul>
<li>Ta</li>
<li>Xgboot</li>
<li>Imblearn</li>
<li>Pandas</li>
<li>Json</li>
<li>Requests</li>
<li>Seaborn</li>
<li>Matplotlib</li>
</ul>

The project was built and run using the Anaconda distribution of Python and Jupyter notebooks.
### Project Motivation
The idea being explored by this project is the use of machine learning algorithms which recognize patterns for classification problems to identify patterns of Bitcoin prices associated with increases in the near term. Such a pattern recognition model would essentially use a technical analysis approach to price prediction as an alternative to the more common time-series models. This project uses an XG-boost classification algorithm to predict Bitcoin daily price highs.<br>

The project components include:
<ul>
<li>An API call to download training data</li>
<li>Exploration of data features</li> 
<li>Feature Engineering in the training data set</li>
<li>Optimization of engineered feature characteristics</li>
<li>Fitting and optimization of the model with Pipeline and GridSearch cross-validation</li>
</ul>

### Repository File Descriptions
The repository for this project includes a Jupyter notebook saved as .ipynb and .html files and a csv file of historical bitcoin price data.

### Results
An XGBoost model was trained to use price patterns and technical indicators to predict if the subsequent day's Bitcoin price high will be higher than the current day. After optimization the model demonstrating an accuracy of 0.764 on test data. Additionally, insights regarding features of the data set and their predictive capabilities for classification type cryptocurrency models were derived in this study which could inform future projects concerning market price prediction.

### Medium Blog Post

The technical details of the project and main insights from it are described in a Medium Blog post available [here](https://medium.com/@merwijas/bitcoin-daily-high-prediction-b7d98a433a07). 

### Licensing, Authors, Acknowledgements, etc.
I'd like to acknowledge and thank Udacity for the project workspace and supporting materials.

