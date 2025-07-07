# 🚢 Titanic Survival Prediction using Naive Bayes

````markdown

This project builds a classification model using the **Naive Bayes algorithm** to predict whether a passenger survived the Titanic disaster. The dataset is preprocessed and passed through a probabilistic classifier for binary classification.

---

## 📊 Dataset

The **Titanic dataset** typically includes:
- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Sex`: Male/Female
- `Age`
- `Fare`
- `SibSp`, `Parch`
- `Embarked`
- `Survived`: Target (1 = Survived, 0 = Not)

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` (optional)
- `seaborn` (optional)

---
````
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-naive-bayes.git
   cd titanic-survival-naive-bayes
   ```
2. Open the notebook:

   ```bash
   jupyter notebook Titanic-Survival-Prediction-Naive-Bayes.ipynb
   ```

3. (Optional) Run Python script (if converted):

   ```bash
   python titanic_nb_classifier.py
   ```

---

## 🧠 Model Used

* **Gaussian Naive Bayes** from `sklearn.naive_bayes`
* Trained using selected features (e.g., Pclass, Sex, Age, Fare)
* Predicts whether a passenger survived (binary classification)

---

## 🔍 Workflow

* Load and clean dataset
* Handle missing values (e.g. age)
* Encode categorical variables (e.g. Sex, Embarked)
* Train/test split
* Train Naive Bayes model
* Evaluate predictions using accuracy and confusion matrix

---

## 📈 Results

* Model predicts survival with good accuracy using basic features
* Demonstrates the simplicity and speed of Naive Bayes on real-world data

---

## 📂 File Structure

```
titanic-survival-naive-bayes/
│
├── Titanic-Survival-Prediction-Naive-Bayes.ipynb   # Main notebook
├── titanic.csv                                     # Dataset (if included)
├── README.md                                       # Project overview
```

---

## 🤝 Contributing

Suggestions for better feature engineering, advanced models, or deployment ideas are welcome!

---

## 📜 License

[MIT License](LICENSE)

---

