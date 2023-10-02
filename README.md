
# Used Car Price Prediction

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/used-car-price-prediction)
![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/used-car-price-prediction)
![GitHub](https://img.shields.io/github/license/yourusername/used-car-price-prediction)

## Table of Contents
- [Project Description](#project-description)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project is an end-to-end Machine Learning application for predicting used car prices. It uses a RandomForest Regressor model to predict the price of a used car based on various features such as year, mileage, fuel type, and more. The model is deployed using Flask, allowing users to input car details and get price predictions.

## Demo

[Link to Live Demo]([https://your-app-url.com](https://screenapp.io/app/#/library/64e085cd02bc08233a83c474/default/57c418d3-45dd-4a8e-b8e6-2fc7bf6414d7))

[Link to Demo Video](https://www.youtube.com/watch?v=yourvideo)

[Demo Screenshot](/screenshots/demo.png)

## Technologies Used

- Python
- Flask
- scikit-learn
- Pandas
- NumPy
- HTML/CSS
  

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/used-car-price-prediction.git
Change directory to the project folder:

bash
Copy code
cd used-car-price-prediction
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
Activate the virtual environment:

Windows:
bash
Copy code
.\venv\Scripts\activate
macOS/Linux:
bash
Copy code
source venv/bin/activate
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
Start the Flask application:

bash
Copy code
python app.py
Access the web app in your browser at http://localhost:5000.

Enter the car details and click the "Predict" button to get the predicted price.

API Documentation
The project includes a RESTful API for making predictions programmatically. You can access the API endpoints as follows:

Endpoint: /predict
Method: POST
Request Format: JSON
Example Request:
json
Copy code
{
  "Year": 2018,
  "Mileage": 50000,
  "Fuel_Type": "Petrol",
  "Transmission": "Manual",
  "Owner": 1,
  "Brand": "Toyota"
}
Response Format: JSON
Example Response:
json
Copy code
{
  "predicted_price": 7500.0
}
Contributing
Contributions are welcome! Please create a new issue or submit a pull request.

License
This project is licensed under the MIT License.

