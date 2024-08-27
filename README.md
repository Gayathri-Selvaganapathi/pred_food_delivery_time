# Food Delivery Time Prediction
This project predicts the delivery time for food orders based on various features like restaurant location, delivery distance, weather conditions, etc. The model is trained on historical delivery data and can be used to improve delivery logistics by predicting more accurate delivery times.

## Project Structure
1. app.py: This is the main file that runs the Flask web application. The application provides an interface where users can input delivery details and get the predicted delivery time.

2. functions.py: This file contains helper functions used across the project, including data preprocessing, feature engineering, and the actual prediction logic.

3. Food-Delivery-Predicting.ipynb: A Jupyter notebook that contains the exploratory data analysis (EDA), model development, and evaluation process. It includes steps to clean the data, feature selection, model training, and evaluation.

4. Dataset: The dataset used to train the machine learning model. It includes features such as restaurant location, delivery distance, weather conditions, and actual delivery time.

## Setup Instructions
1. Clone the repository
``` bash
git https://github.com/Gayathri-Selvaganapathi/pred_food_delivery_time.git
cd pred_food_delivery_time
```

2. Unzip the src file

3. Set up the virtual environment
Use conda to create a virtual environment based on the environment.yml file:


```bash
conda env create -f environment.yml
conda activate chatbot-env
```

Alternatively, use pip to install the dependencies listed in requirements.txt:

```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook
To explore the data and understand the model, open the Jupyter notebook:

```bash
Copy code
jupyter notebook Food-Delivery-Predicting.ipynb
```

5. Run the Streamlit App
To start the application:

```bash
streamlit run app.py
```

## How to Use the Application
1. Input Data: Fill in the details such as restaurant location, delivery distance, and weather conditions.
2. Get Prediction: Click the "Predict" button to receive the estimated delivery time.
3. Analyze Results: The application will display the predicted delivery time based on the input data.

## Model Training
The machine learning model is trained using the dataset provided in train.csv. The notebook (Food-Delivery-Predicting.ipynb) details the entire process, including:

    * Data Cleaning
    * Feature Engineering
    * Model Selection
    * Model Training
    * Model Evaluation

## Future Work
* Improving Model Accuracy: Experiment with more advanced models and hyperparameter tuning.*
* Real-time Predictions: Integrate real-time data feeds for making live predictions.
* Deployment: Deploy the application on a cloud platform like AWS or Heroku for wider access.

## License
This project is licensed under the MIT License

