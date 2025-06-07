# Credit Score Prediction Using Machine Learning

This project aims to predict a person's credit score category (`Excellent`, `Good`, `Fair`, or `Poor`) using machine learning techniques. The model helps assess whether a person is eligible for a loan based on features like age, income, and payment history.

## 🔍 Project Overview

Credit scoring is a statistical analysis performed by lenders and financial institutions to determine the creditworthiness of a borrower. In this project, we:

- Use a dataset (`credit_scoring.csv`) containing various customer features.
- Train a classification model to predict credit score categories.
- Evaluate the model using a **confusion matrix**.
- Demonstrate prediction on an individual with **age 50** to determine loan eligibility.

## 📁 Dataset

The dataset used in this project is:

**File:** `credit_scoring.csv`

**Features include:**
- Age
- Income
- Number of Defaults
- Late Payments
- Credit Utilization
- Credit History Length
- And other relevant financial attributes

**Target Variable:**  
`Credit_Score` - This is a categorical value with four classes:
- Excellent
- Good
- Fair
- Poor

## 💡 Objective

To build a machine learning model that can classify the credit score of individuals and help determine loan eligibility.

## 🧪 Model and Evaluation

- Preprocessing is done using standard scaling and encoding as needed.
- A **Random Forest Classifier** (or any other classifier) is used for prediction.
- Performance is evaluated using a **Confusion Matrix** which gives a clear view of model performance across the four credit score categories.


The model takes into account other features as well (e.g., income, credit utilization) and categorizes the individual into one of the four credit score classes.

If the predicted credit score is:

- `Excellent` or `Good` → **Eligible for Loan**
- `Fair` or `Poor` → **Not Eligible for Loan**

This decision is based on creditworthiness implied by the classification.

---

## 📊 Methodology

1. **Data Preprocessing**
   - Handle missing values
   - Normalize numerical columns
   - Encode categorical values if needed

2. **Model Training**
   - Split dataset into training and testing sets
   - Train using classification algorithms (e.g., Decision Tree, Random Forest, etc.)

3. **Evaluation**
   - Confusion Matrix to evaluate model accuracy
   - Precision, Recall, and F1-Score used for performance metrics

4. **Prediction**
   - User input (e.g., Age = 50) is classified
   - Loan eligibility is decided based on the classification result

---

## 🔍 Confusion Matrix Classes

The confusion matrix is used to classify predicted vs actual labels among the following:

- `Excellent`
- `Good`
- `Fair`
- `Poor`

This helps in understanding how well the model is distinguishing between credit score categories.

---

## 🚀 How to Run

```bash
git clone https://github.com/rameshadigakunjal/Credit_Score.git
cd Credit_Score
 Run your Python code that handles data preprocessing, training, and prediction.

```
##Make sure to have the required libraries installed:
```bash
git clone https://github.com/rameshadigakunjal/Credit_Score.git
cd Credit_Score
 pip install pandas numpy scikit-learn matplotlib seaborn
```
##📈 Sample Output
```yaml
 Input: Age = 50
 Predicted Credit Score: Good
 Loan Eligibility: ✅ Eligible

```
## 🌱 Future Work

- Improve accuracy using **hyperparameter tuning** and **cross-validation**
- Introduce **deep learning models** for large-scale datasets
- Add **Streamlit web interface** for real-time predictions
- Deploy the model using **Flask/Django and Docker**

---

## 🤝 Contributing

Contributions are welcome!

### How to Contribute:

- Fork the repository  
- Create your feature branch (`git checkout -b feature-name`)  
- Commit your changes (`git commit -am 'Add feature'`)  
- Push to the branch (`git push origin feature-name`)  
- Open a Pull Request


### 🙏 Thank You 🙏

⭐ Thank you for visiting the repository! If you found it helpful, consider starring it! ⭐

Feel free to open issues or contribute! Let's improve this together 💪




