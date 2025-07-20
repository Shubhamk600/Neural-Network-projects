# Customer Churn Prediction using ANN 

This project focuses on predicting customer churn using an Artificial Neural Network (ANN) model built in Python with TensorFlow and Keras. The model helps businesses identify customers likely to leave, allowing proactive retention strategies.

##  Project Structure

```
Customer_Churn_ANN_Modelling/
├── Customer_Churn_ANN_Modelling.ipynb
├── README.md
```

##  Objective

To build a deep learning classification model that predicts whether a customer will churn based on their attributes like tenure, services, contract type, and payment method.

---

## 🛠 Tools & Technologies

- Python 
- Pandas, NumPy
- Matplotlib, Seaborn
- TensorFlow, Keras (Sequential API)
- Scikit-learn (for preprocessing & evaluation)

---

##  Model Overview

- Input: Customer data (features like contract type, internet service, monthly charges, etc.)
- Model: ANN with 1 input layer, 2 hidden layers, and 1 output layer (Sigmoid)
- Output: Probability of churn (binary classification)

---

##  Workflow

1. **Data Preprocessing**
   - Handle categorical features with encoding
   - Scale numerical features
   - Split into train/test sets

2. **Model Building**
   - Defined an ANN using `Sequential()`
   - Used ReLU and Sigmoid activations
   - Compiled using `adam` optimizer and `binary_crossentropy`

3. **Training & Evaluation**
   - Trained the model on training data
   - Evaluated accuracy on test set
   - Plotted confusion matrix and metrics

---

##  Results

- Accuracy: ~84–87%
- Model performs well in predicting churners vs non-churners

---

##  Running the Notebook

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `Customer_Churn_ANN_Modelling.ipynb` in Jupyter or Colab.

---

##  Contributing

Feel free to fork the repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss the changes.

---


