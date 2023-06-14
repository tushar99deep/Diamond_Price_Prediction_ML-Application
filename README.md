# Diamond Price Prediction


## Project Overview
Diamond Price Prediction is a machine learning application that predicts the price of a diamond based on its size, color, cut, and other input features. It utilizes a machine learning model trained on a diamond dataset to make accurate price predictions. The application was developed using Python and deployed on AWS for public access.

## Dataset
The diamond dataset used for training and testing the model is sourced from [Dataset Source]. It contains information about various attributes of diamonds such as carat weight, color, cut, clarity, depth, table, and price. This dataset was used to train and evaluate the machine learning model for accurate price predictions.
Context
This classic dataset contains the prices and other attributes of almost 54,000 diamonds. It's a great dataset for beginners learning to work with data analysis and visualization.

Content
price price in US dollars (\$326--\$18,823)

carat weight of the diamond (0.2--5.01)

cut quality of the cut (Fair, Good, Very Good, Premium, Ideal)

color diamond colour, from J (worst) to D (best)

clarity a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

x length in mm (0--10.74)

y width in mm (0--58.9)

z depth in mm (0--31.8)

depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

table width of top of diamond relative to widest point (43--95)

## Model Architecture
The machine learning model employed in this application is a [model architecture]. It takes as input the diamond's features such as carat weight, color, cut, and other relevant attributes and produces a predicted price as the output. The model was trained using supervised learning techniques and optimized to achieve high accuracy and predictive performance.

## Deployment
The application is deployed on AWS to make it accessible to users. The deployment process involves setting up an AWS EC2 instance and configuring it with the necessary software dependencies. The application is hosted on the EC2 instance, allowing users to access it via a web interface or API endpoint.

## Usage
To access the Diamond Price Prediction application, follow these steps:

1. Access the application through the following URL: [Application URL].
2. Provide the required input features such as carat weight, color, cut, and other relevant attributes.
3. Click the "Predict" button to obtain the predicted price for the diamond.

## Installation and Setup
To run the Diamond Price Prediction application locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/tushar99deep/Diamond_Price_Prediction_ML-Application
```

2. Navigate to the project directory:

```
cd https://github.com/tushar99deep/Diamond_Price_Prediction_ML-Application
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Run the application:

```
python app.py
```

5. Access the application via http://localhost:5000 in your web browser.

## Technologies Used
The Diamond Price Prediction application utilizes the following technologies:

- Python: Programming language used for application development.
- Machine Learning Libraries: Used for model training and prediction.
- Flask: Web framework used for building the application.
- AWS: Cloud platform used for deployment.


## Contribution
Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please submit a pull request or open an issues.
