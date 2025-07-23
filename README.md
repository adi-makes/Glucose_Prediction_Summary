
# Glucose Level Prediction 💉📊

This project focuses on predicting **glucose levels** using health-related indicators from the **Framingham Heart Study** dataset. It includes data cleaning, visualization, model building, evaluation, and prediction analysis.

## 📁 Project Structure

- `Glucose_Prediction_Summary.ipynb` – Jupyter Notebook containing:
  - Data loading and cleaning
  - Exploratory data analysis (EDA)
  - Model training and testing (Logistic Regression, Decision Tree, Random Forest)
  - Evaluation using classification and regression metrics
  - Feature importance visualization

## 📊 Dataset

- **Source**: Framingham Heart Study Dataset (`framingham.csv`)
- Contains medical records and lifestyle data including:
  - `glucose`
  - `age`, `BMI`, `heartRate`, `totChol`, `sysBP`, `diabeteMed`, etc.
- Target: Glucose levels (continuous or classified range)

## 🔧 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy** – Data processing
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-learn** – Machine Learning models and evaluation

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/glucose-level-prediction.git
   cd glucose-level-prediction
   ```

2. Add the dataset file `framingham.csv` to the project directory.

3. Launch the notebook:
   ```bash
   jupyter notebook Glucose_Prediction_Summary.ipynb
   ```

4. Run all cells sequentially to view results and predictions.

## 🧠 Key Features

- Handles null values and scales features
- Performs both classification and regression modeling
- Compares performance using:
  - Accuracy
  - Confusion Matrix
  - Mean Squared Error (MSE)
  - R² Score

## 📌 Future Improvements

- Tune hyperparameters using `GridSearchCV`
- Integrate real-time glucose prediction dashboard
- Add more models like Gradient Boosting or XGBoost
- Explore classification vs regression comparison

## 🧾 License

This project is open-source and available under the [MIT License](LICENSE).
