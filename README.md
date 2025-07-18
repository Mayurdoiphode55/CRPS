#__Credit Risk & Loan Approval Prediction Dashboard 🏦__#

An interactive web dashboard built with Streamlit to predict the probability of a loan being approved based on applicant details. This project demonstrates the end-to-end process of data cleaning, feature engineering, model training, and deployment into a user-friendly application.

📸 Screenshot
It is highly recommended to add a screenshot of your running dashboard here. It makes a huge difference!

__✨ Features__

Exploratory Data Analysis (EDA): Interactive charts and graphs to explore the relationships between applicant features and loan approval status.

Real-time Prediction: A user-friendly form to input an applicant's details and receive an instant prediction on their loan approval status.

Prediction Probability: Shows the model's confidence in its prediction (e.g., 85% probability of approval).

Clean & Responsive UI: A simple and intuitive interface that works on different screen sizes.

__🛠️ Tech Stack__

Backend & Modeling:

Python: Core programming language.

Pandas: For data manipulation and analysis.

Scikit-learn: For building the machine learning pipeline (preprocessing, modeling).

XGBoost / RandomForest: The algorithm used for the classification model.

Joblib / Pickle: For saving and loading the trained model pipeline.

Frontend & Deployment:

Streamlit: For building and serving the interactive web application.

Plotly Express: For creating interactive data visualizations.

📂 Project Structure

Credit_Risk_Prediction_Project/

│

├── .venv/                  # Virtual environment folder

├── train.csv               # Training dataset

├── test.csv                # Testing dataset

├── Credit_Risk_Prediction_Project.ipynb  # Jupyter Notebook for exploration and model training

├── risk_model.joblib       # The saved, trained model pipeline

├── dashboard.py            # The Streamlit application script

├── requirements.txt        # List of Python dependencies

└── README.md               # You are here!

__⚙️ Setup and Installation__

To run this project on your local machine, follow these steps:

1. Clone the Repository:

<pre><code>bash git clone [https://github.com/Mayurdoiphode55/Credit_Risk_Prediction_Project.git]</code></pre>

(https://github.com/Mayurdoiphode55/Credit_Risk_Prediction_Project.git)

<pre><code> cd Credit_Risk_Prediction_Project </code></pre>

2. Create and Activate a Virtual Environment:

This keeps your project dependencies isolated.

# For Windows

python -m venv venv </code></pre>

<pre><code> .\venv\Scripts\Activate.ps1 </code></pre>

# For macOS/Linux

<pre><code> python3 -m venv venv </code></pre>

<pre><code> source venv/bin/activate python </code></pre>



3. Install Dependencies:

This command installs all the necessary libraries listed in requirements.txt.

<pre><code>pip install -r requirements.txt</code></pre>

4. Run the Streamlit App:

This will start the web server and open the dashboard in your browser.

<pre><code>streamlit run dashboard.py </code></pre>

📈 Model Details

The prediction model is a RandomForestClassifier (or XGBClassifier, whichever you used) wrapped in a Scikit-learn Pipeline. The pipeline handles all preprocessing steps, including:

Imputing missing values for both numerical and categorical features.

Scaling numerical features using StandardScaler.

Encoding categorical features using OneHotEncoder.

The model achieved an accuracy of [Enter Your Accuracy Here, e.g., 82%] on the validation set.

👤 Author

Mayur Doiphode

GitHub: @Mayurdoiphode55


📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
