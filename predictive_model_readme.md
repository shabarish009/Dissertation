# Predictive Model for Optimizing Pre-sessional English Course Durations at BIA

This project enhances the decision-making process at Birmingham International Academy (BIA) by using a predictive model to optimize Pre-sessional English course durations. The model ensures students meet English proficiency requirements for their academic programs while considering individual needs like budget and time constraints.

---

## Key Features

- **Cautious Course Duration Recommendation:**  
  This feature assesses a student's pre-course history, including IELTS scores, gender, nationality, and future academic course, to find the shortest possible course duration for success. If needed, it suggests a longer duration to lower the risk of failure.

- **Individual Section Prediction and Risk Management:**  
  The model predicts student performance in each section of the Pre-sessional course and recommends a longer duration if there's a risk of failing. It also provides warnings for students who are borderline passers.

- **Batch Processing for Multiple Students:**  
  The model can extend its risk management capabilities to handle a group of students, allowing BIA to efficiently assess and support multiple students at the same time.

---

## How It Works

This project uses a quantitative research design to develop and validate a predictive model aimed at optimizing the Pre-sessional English courses at BIA.

The model is built using several machine learning techniques, including:

- **ElasticNet:** A regularized regression model that handles multicollinearity and performs variable selection.  
- **Support Vector Regressor (SVR):** Used for its ability to capture non-linear relationships in data, which improves the model's predictive accuracy.  
- **Huber Regressor:** Chosen for its robustness against outliers, this model combines the benefits of least squares and absolute loss, making it useful for datasets with anomalies.

The model's development follows a structured approach:

1. **Data Collection:** Historical data from BIA, including IELTS scores, demographic information, and course outcomes, is gathered.  
2. **Data Preprocessing:** The data is cleaned by handling missing values, standardizing numerical features, and encoding categorical variables.  
3. **Model Training:** The data is split into training and testing sets, and the models are trained using cross-validation to optimize hyperparameters.  
4. **Model Evaluation:** The models are evaluated using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).  
5. **Implementation:** The best-performing model is used to make predictions on new data, helping with course duration recommendations and identifying students at risk.

---

## Project Aim

The main goal of this project is to create a comprehensive predictive model that helps BIA make informed decisions about course durations and manage student outcomes effectively. The specific objectives include:

- **Performance Prediction:** To accurately predict individual student outcomes in the different sections of the Pre-sessional course (Listening, Reading, Writing, Speaking) based on pre-course data such as IELTS scores and demographic factors.  
- **Cautious Course Duration Recommendation:** To offer data-driven recommendations for the shortest possible course duration that ensures a student's success, especially when they request a shorter course.  
- **Risk Management:** To identify students who are at risk of failing and suggest longer durations when needed.  
- **Batch Processing:** To make it easier to evaluate multiple students at once, which streamlines the decision-making process and improves operational efficiency.

---

## Installation and Usage

To run this project locally, follow these steps:

1. Clone the repository:  
   ```bash
   git clone https://github.com/shabarish009/Dissertation.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd Dissertation
   ```

3. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. Run the main script:  
   ```bash
   python main.py
   ```

---

## Acknowledgements

We would like to thank the Birmingham International Academy (BIA) for providing the necessary data and resources for this project. A special thanks goes to the Director of the Pre-sessional Program for their valuable insights. We also appreciate the guidance and support from our academic mentors and colleagues, whose contributions were essential to the success of this project.

