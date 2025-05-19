# Air-quality

---

Air Level Prediction

This project predicts the air pollution level using machine learning techniques. It processes environmental data to forecast air quality metrics, helping assess and manage pollution risks.

Features

Data preprocessing and exploratory data analysis (EDA)

Feature selection and normalization

Training models using:

Linear Regression

Decision Tree Regressor

Random Forest Regressor


Evaluation using R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE)

Visualizations of actual vs predicted values


Dataset

The dataset includes environmental variables such as:

PM2.5

PM10

NO2

CO

Temperature, Humidity, etc.


Note: The dataset is loaded from a CSV file. Please ensure air_dataset.csv is present in the same directory as the notebook or adjust the path accordingly.

Installation

Clone the repository and install dependencies:

git clone https://github.com/yourusername/air-level-prediction.git
cd air-level-prediction
pip install -r requirements.txt

Usage

Run the Jupyter Notebook:

jupyter notebook Air_level_predection.ipynb

Explore the notebook to understand preprocessing steps, model training, and evaluation.

Results

The Random Forest Regressor achieved the best performance among all models with high R² score and low MAE/MSE, indicating reliable prediction capabilities.

Requirements

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

Jupyter Notebook


License

This project is licensed under the MIT License.

Author

artheeswari a 


---


