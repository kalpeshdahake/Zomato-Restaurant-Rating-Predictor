# Zomato-Restaurant-Rating-Predictor

<!DOCTYPE html>
<html>

<head>
    <title>End-To-End Deployment of Zomato Restaurant Ratings</title>
</head>

<body>

<h1>Main Objective:</h1>

<p>The main agenda of this project is:</p>

<ol>
    <li>Perform extensive Exploratory Data Analysis (EDA) on the Zomato Dataset</li>
    <li>Build an appropriate Machine Learning Model that will help various Zomato Restaurants to predict their respective Ratings based on certain features</li>
    <li>DEPLOY the Machine learning model via Flask that can be used to make live predictions of restaurant ratings</li>
</ol>

<h1>STEPS:</h1>

<h2>A. EDA and Model Building Part</h2>

<ol>
    <li>Load the dataset and perform the necessary EDA in your Jupyter notebook or google colab</li>
    <li>Build your Machine learning algorithm and save your model using "pickle"</li>
</ol>

<h2>B. Deployment Part</h2>

<ol>
    <li>In this project we will be using "pycharm", however, feel free to use any IDE that you are comfortable with (e.g. you can use sublime text editor to achieve the same)</li>
    <li>Install your favorite IDE (e.g. pycharm) if not installed already. Download pycharm IDE: <a href="https://www.jetbrains.com/pycharm/download/">Download PyCharm</a></li>
    <!-- Add installation steps if needed -->
    <li>Either create a new project or open an existing project</li>
    <!-- Add steps for setting up the project and interpreter -->
    <li>Once all the Packages are loaded, right click Model.py then Run</li>
    <!-- Add steps for running the Model.py -->
    <li>Same way, right click and Run App.py</li>
    <!-- Add steps for running the App.py -->
    <li>Copy the URL - <a href="http://127.0.0.1:5000/">http://127.0.0.1:5000/</a> and open it in a web browser</li>
    <!-- Add steps for using the web app -->
    <li>After the validation, stop the URL as mentioned below</li>
    <!-- Add steps for stopping the app -->
    <li>Optional: You can create a virtual environment to avoid any conflicts in library dependencies (recommended)</li>
    <!-- Add steps for setting up a virtual environment -->
    <li>Specifically, install Flask: Use: pip install flask</li>
    <!-- Add steps for installing Flask -->
    <li>Files you will need:</li>
    <!-- List the required files -->
</ol>

<h2>File Descriptions</h2>

<ul>
    <li><strong>Model.py:</strong> This file contains the code for building our model that is used in predicting the restaurant ratings</li>
    <li><strong>csv file:</strong> This contains our data that we have already cleaned and saved</li>
    <li><strong>template file:</strong> The template file contains the HTML and CSS documents used in building our web app</li>
    <li><strong>App.py:</strong> This contains the Flask API's that receives restaurant details via a GUI/API calls, then makes the prediction of restaurant ratings based on our model and returns the rate</li>
</ul>

<!-- Add instructions for creating the required files and folders -->

</body>

</html>
