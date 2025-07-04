
# 🎓 College Feedback Classifier

This project is a Python-based classifier that helps educational institutions automatically categorize open-ended student feedback into relevant departments — **Academics**, **Facilities**, or **Administration** — enabling structured analysis and effective decision-making.

---

## ✅ Features

* Generates 1000+ sample feedback entries for training
* Trains a machine learning model (Logistic Regression with TF-IDF)
* Accepts real-time user input and classifies the department
* Saves all feedback with predictions to a CSV file
* Easy to run on Google Colab, VSCode, or Jupyter Notebook

---

## 🧰 Tools & Technologies

* Python 3.x
* Pandas
* Scikit-learn (Logistic Regression, TF-IDF, train-test split)
* Google Colab (optional)

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/college-feedback-classifier.git
cd college-feedback-classifier
```

2. Install required dependencies:

```bash
pip install pandas scikit-learn
```

3. Run the classifier script:

```bash
python classifier.py
```

---

## 💬 Sample Input/Output

```
Enter Your Feedback: The canteen food is unhygienic.
📌 Predicted Department: Facilities
🙏 Thank you for your feedback! We will notify the Facilities department to take necessary action.
```

---

## 📊 Dataset

* The dataset is synthetically generated with over 1000 feedback entries equally distributed among:
  - **Academics**
  - **Facilities**
  - **Administration**

---

## 🔮 Future Enhancements

* Accept external CSV datasets
* Integrate with Google Forms or College ERP systems
* Use deep learning for contextual classification
* Visual dashboard to summarize categorized feedback
* Multi-language feedback handling

---

## 📄 License

This project is developed for academic demonstration and educational use only.
