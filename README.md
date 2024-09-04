# Sales-Forecaster
Sales-Forecaster is an advanced sales prediction tool designed to help businesses forecast their sales using machine learning techniques. This application leverages an LSTM-based model to deliver accurate sales predictions for various business types, with a user-friendly interface for easy input and result access.

## Features
- **LSTM-Based Sales Prediction**: Utilizes a Long Short-Term Memory (LSTM) model to predict sales across different types of businesses, providing reliable forecasts.
- **Automated Data Pipeline**: A robust data pipeline that automates data collection, preprocessing, and feature engineering, ensuring that the sales forecasting model is fed with clean and relevant data.
- **CSV File Input and Prediction Delivery**: Users can upload a CSV file containing their sales data and target labels, and the model will predict future sales. The predictions are then emailed to the user, making them accessible from anywhere at any time.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Django
- **Machine Learning**: TensorFlow

## Getting Started
To get started with Sales-Forecaster, clone the repository and follow the setup instructions in the `README.md` file. Ensure you have the required dependencies installed and configure your environment for TensorFlow.

## Setup Instructions
Follow these steps to set up the Sales-Forecaster project on your local machine:
### 1. Clone the Repository
First, clone the repository to your local machine using the following command:
```bash
git clone https://github.com/yourusername/sales-forecaster.git
cd sales-forecaster
```
### 2. Create and Activate a Virtual Environment (Optional but Recommended)
It's a good practice to use a virtual environment to manage your project dependencies. You can create and activate one using the following commands:

for windows :-
```bash
python -m venv venv
venv\Scripts\activate
```
for macOS/Linux :-
```bash
python3 -m venv venv
source venv/bin/activate
```
### 3. Install Dependencies
Install the required dependencies using pip:
```bash
pip install -r requirements.txt
```
This command will install all the necessary packages listed in the requirements.txt file, including Django, TensorFlow, and other dependencies.
### 4. Configure the Project
You may need to set up some configuration files before running the project:
Database Configuration: Update the settings.py file in the Django project to configure the database if needed (e.g., SQLite, PostgreSQL).
Email Settings: Configure the email backend in settings.py to enable the sending of prediction results via email.
TensorFlow Model: Ensure that the TensorFlow model is properly set up. If you have a pre-trained model, place it in the designated directory, or follow the instructions to train the model.
### 5. Apply Migrations
Before running the project, apply any database migrations:
```bash
python manage.py migrate
```
### 6. Run the Development Server
Start the Django development server to run the application locally:
```bash
python manage.py runserver
```
Visit http://127.0.0.1:8000/ in your web browser to view the application.
### 7. Upload CSV and Get Predictions
Navigate to the section of the application where you can upload a CSV file.
After uploading the file, the model will process the data and email the predictions to the address specified.
### 8. Deactivate the Virtual Environment (Optional)
When you're done working with the project, you can deactivate the virtual environment:
```bash
deactivate
```
## Contributing
Contributions are welcome!
