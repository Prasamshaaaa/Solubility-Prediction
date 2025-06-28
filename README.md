# Solubility Prediction Project

This project predicts the solubility (`logS`) of chemical compounds based on their molecular descriptors using machine learning models.

---

## What This Project Does

- Loads the Delaney Solubility Dataset containing molecular descriptors and experimentally measured solubility (`logS`).
- Preprocesses the data and splits it into training and test sets.
- Trains two regression models — Linear Regression and Random Forest Regressor — to predict solubility.
- Evaluates the models using Mean Squared Error (MSE) and R² score on both training and test datasets.
- Visualizes the predicted solubility values against the experimental values.

---

## Tools and Libraries Used

- **Python 3.7+**
- **Pandas** — data loading and preprocessing
- **Scikit-learn** — machine learning models and evaluation metrics
- **Matplotlib** and **NumPy** — visualization and numerical computations

---

## Model Performance Comparison

| Model              | Training MSE | Training R² | Test MSE | Test R² |
|--------------------|--------------|-------------|----------|---------|
| Linear Regression   | 1.0075       | 0.7645      | 1.0207   | 0.7892  |
| Random Forest       | 1.0282       | 0.7597      | 1.4077   | 0.7092  |

**Interpretation:**  
The Linear Regression model demonstrates better performance on the test set, achieving higher R² and lower MSE, suggesting it generalizes better on unseen data compared to the Random Forest model.

---

## How to Run This Project

1. Clone the repository:
    ```bash
    git clone [https://github.com/your-username/solubility-prediction.git](https://github.com/Prasamshaaaa/Solubility-Prediction.git)
    cd solubility-prediction
    ```

2. Install required Python packages:
    ```bash
    pip install pandas scikit-learn matplotlib numpy
    ```

3. Open and run the notebook `solubility-prediction.ipynb` in Google Colab or Jupyter Notebook.

---

## File Structure

