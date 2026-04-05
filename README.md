# Cancer Stage Prediction using Machine Learning

## 📌 Overview

This project uses a **Random Forest Classifier** to predict the stage of cancer based on patient data such as blood group, gender, and reported symptoms. The model is trained on a dataset (`aiml.csv`) and allows interactive user input for real-time predictions.

---

## 🚀 Features

* Data preprocessing with handling of missing values
* Label encoding for categorical variables
* Machine learning model using Random Forest
* Accuracy evaluation of the model
* Interactive CLI-based prediction system
* Flexible symptom input (up to 8 symptoms)

---

## 🧠 Technologies Used

* Python
* Pandas
* Scikit-learn

---

## 📂 Dataset

The dataset file (`aiml.csv`) includes the following columns:

* `Blood Group`
* `Gender`
* `Cancer Stage` (Target variable)
* `Symptom 1` to `Symptom 8`

⚠️ **Important Note:**
This dataset is **not sourced from real-world medical records**. It was **artificially created specifically for this project** for learning and demonstration purposes only.

> Ensure there are no missing values or they will be dropped during preprocessing.

---

## ⚙️ Installation

1. Clone this repository or copy the script
2. Install required dependencies:

```bash
pip install pandas scikit-learn
```

3. Place your dataset file (`aiml.csv`) in the same directory

---

## ▶️ How to Run

Run the Python script:

```bash
python your_script_name.py
```

---

## 🧪 Model Workflow

1. Load dataset using Pandas
2. Remove missing values
3. Encode categorical features using LabelEncoder
4. Split data into training and testing sets (80/20)
5. Train a Random Forest Classifier
6. Evaluate model accuracy
7. Accept user input for prediction

---

## 💡 User Input Guide

When prompted:

* Enter your **name**
* Provide your **blood group** (e.g., A+, B-, O+)
* Enter your **gender** (Male/Female)
* Input up to **8 symptoms**, or type `done` to finish early

---

## ⚠️ Important Notes

* Symptoms must match those present in the training dataset
* Unknown symptoms will be ignored with a warning
* The model accuracy depends on dataset quality
* This tool is for **educational purposes only** and should not replace professional medical advice

---

## 📊 Example Output

```
Model Accuracy: 87.50%
Predicted Cancer Stage: Stage II
```

---

## 🛠️ Future Improvements

* Add GUI or web interface
* Improve symptom handling with NLP
* Support more flexible input formats
* Use larger and more diverse datasets
* Model optimization and tuning

---

## 📜 License

This project is open-source and available for educational and research purposes.

---

## 🙌 Acknowledgements

Thanks to the open-source community and contributors of:

* Scikit-learn
* Pandas

---

## 📬 Contact

For questions or suggestions, feel free to reach out.

---
