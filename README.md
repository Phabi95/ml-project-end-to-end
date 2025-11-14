# End-to-End Wine Quality Prediction (ML Project)

This project is a complete end-to-end Machine Learning application that predicts the quality of wine based on its chemical properties. It is built using a **Flask** web server for the user interface and an **ML pipeline** for the prediction model.

##  Project Goal

The goal of this project is to demonstrate a full end-to-end ML workflow. This includes:
1.  Training a machine learning model.
2.  Saving the model and its pipeline.
3.  Building a simple web application with Flask to serve the model.
4.  Allowing a user to get real-time predictions by entering data into a web form.

##  Features

* **Web Interface:** A simple HTML form (at the `/` route) to input 11 chemical features of wine.
* **Prediction:** A `/predict` route that takes the form data, processes it, and returns the predicted quality.
* **Training:** A `/train` route that can be used to trigger a full retraining of the model by running the `main.py` pipeline.

## Technologies Used

* **Language:** Python
* **Libraries:**
    * Flask (for the web server)
    * scikit-learn (for the ML pipeline)
    * Pandas & Numpy (for data manipulation)
* **Tools:** Git, GitHub, VSCode, Virtual Environments

##  Installation & Usage

Follow these steps to run the project on your local machine.

### 1. Clone the repository

```bash
git clone [https://github.com/Phabi95/ml-project-end-to-end.git](https://github.com/Phabi95/ml-project-end-to-end.git)
cd ml-project-end-to-end

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate

### 3. Install dependencies

This project requires several libraries. Make sure you have a requirements.txt file in your repository.

```bash
pip install -r requirements.txt

### 4. Run the Application

Markdown

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate

(On Windows, use: .venv\Scripts\activate)

### 3. Install dependencies

This project requires several libraries. Make sure you have a requirements.txt file in your repository.

(If you don't have one, run this command in your terminal to create it before you upload to GitHub):
Bash

pip freeze > requirements.txt

(For a user downloading the project, they just run):
Bash

pip install -r requirements.txt

### 4. Run the Application

You must run the Flask app to start the web server.

```bash
python app.py

### 5. Access the Web App

Once the server is running, open your web browser and go to:

http://127.0.0.1:8080/

You will see the index.html page with a form.

### 6. Make a Prediction

    Fill in the 11 fields for wine properties (e.g., fixed_acidity, alcohol, etc.).

    Click the "Predict" button.

    The app will process the data and show you the predicted quality on the results.html page.