Credit Card Fraud Detection with Flask and Machine Learning
===========================================================

This project combines web development with Flask as a backend, HTML/CSS for frontend, MongoDB as the database, and machine learning models for credit card fraud detection.

Project Overview
----------------

This project aims to detect fraudulent credit card transactions using machine learning algorithms. It includes a web application built with Flask where users can upload transaction data, which is then processed using machine learning models to detect fraud.

Installation
------------

Prerequisites:
- Python 3.x installed on your system.
- MongoDB installed locally or accessible remotely.
- Git installed to clone the repository.

Steps:
1. Clone the repository:

   git clone https://github.com/valakalpesh/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection

2. Set up Python environment:

   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install dependencies:

   pip install -r requirements.txt

4. Download the dataset:

   - The dataset used in this project is not included in the repository due to size constraints.
   - Download the dataset from https://drive.google.com/file/d/1tUFNkZL9KaHETca5-e_Q6UaCvgHuXcMt/view?usp=drive_link and place it in a directory (data/) in the root of your project.

5. Set up MongoDB:

   - Install MongoDB on your local machine or use a cloud-based MongoDB service.
   - Configure MongoDB connection URI in app.py or a separate configuration file.

6. Run the application:

   python app.py

   The application should now be running locally. Access it at http://localhost:5000 in your web browser.

Project Structure
-----------------

- app.py: Flask application setup and routes and Machine learning models and preprocessing scripts..
- templates/: HTML templates for rendering frontend.
- static/: CSS stylesheets and other static files.
- data/: Directory to store the dataset (not included in repository).

Machine Learning Models
-----------------------

This project uses the following machine learning models from scikit-learn for fraud detection:

- Isolation Forest
- Support Vector Classifier (SVC)
- Logistic Regression

Libraries used include pandas, Flask, pymongo, bcrypt, and werkzeug for file uploads.

Contributing
------------

Contributions are welcome! Please fork the repository and create a pull request for any improvements or fixes.

License
-------

This project is licensed under the MIT License. See the LICENSE file for details.
