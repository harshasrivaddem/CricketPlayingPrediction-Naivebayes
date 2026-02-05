# 🏏 Play Cricket Prediction using Naive Bayes

## 📌 Project Overview
This project demonstrates a **classification problem** where the goal is to predict whether a cricket match can be played based on **weather conditions**.

The dataset contains categorical weather attributes such as outlook, temperature, humidity, and wind. These features are encoded numerically and used to train a **Gaussian Naive Bayes classifier**.

---

## 📊 Dataset Description
The dataset consists of **14 records** with the following features:

| Feature | Description |
|------|-----------|
| Outlook | Sunny, Overcast, Rainy |
| Temperature | Hot, Mild, Cool |
| Humidity | High, Normal |
| Windy | True / False |
| Target | Play Cricket (Yes / No) |

---

## 🔢 Data Preprocessing
Since Naive Bayes works with numerical values:
- Categorical variables were converted to numerical form using **manual encoding**
- Target variable:
  - `Yes → 1`
  - `No → 0`

### Encoded Values Example:
- Outlook: Rainy → 0, Overcast → 1, Sunny → 2
- Temperature: Hot → 0, Mild → 1, Cool → 2
- Humidity: High → 0, Normal → 1
- Windy: False → 0, True → 1

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- Scikit-learn

---

## 🤖 Model Building
- **Algorithm:** Gaussian Naive Bayes
- **Features Used:**  
  `OUTLOOK, TEMPERATURE, HUMIDITY, WINDY`
- **Target Variable:**  
  `PLAY CRICKET`
- **Train-Test Split:**  
  70% Training, 30% Testing
- **Random State:** 10

---

## 📈 Model Performance
- **Accuracy:** **80%**

```python
Accuracy: 0.8

