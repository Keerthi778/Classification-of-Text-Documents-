
# 📝 Text Document Classification using Naive Bayes

This project demonstrates how to classify text documents into categories using the **Naive Bayes** algorithm with the **20 Newsgroups dataset**.  
It leverages **scikit-learn** for preprocessing (TF-IDF vectorization) and building the classifier.

---

## 🚀 Features
- Loads and processes the [20 Newsgroups dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html).
- Text preprocessing using **TF-IDF Vectorization**.
- **Multinomial Naive Bayes** model for classification.
- Evaluates model with **accuracy** and a **classification report**.
- Allows testing with **custom user-input text**.

---

## 📂 Project Structure
```

├── text\_classification\_nb.py  

├── README.md                  

````

---

## 🛠️ Requirements
Install dependencies with:

```bash
pip install scikit-learn pandas numpy
````

---

## ▶️ Usage

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/text-doc-classification-nb.git
cd text-doc-classification-nb
```

### 2. Run the script

```bash
python text_classification_nb.py
```

---

## 📊 Example Output

Sample classification report:

```
              precision    recall  f1-score   support

   alt.atheism       0.95      0.89      0.92       181
  comp.graphics      0.91      0.95      0.93       197
  rec.sport.baseball 0.98      0.96      0.97       202
         sci.med     0.92      0.94      0.93       199
 talk.politics.misc   0.88      0.92      0.90       188

   accuracy                           0.93       967
  macro avg       0.93      0.93      0.93       967
weighted avg       0.93      0.93      0.93       967
```

Custom predictions:

```
"The doctor prescribed new medicine for my headache." → sci.med
"The new graphics card improves rendering performance." → comp.graphics
"The government passed a controversial new law." → talk.politics.misc
"Baseball is my favorite sport and I play every weekend." → rec.sport.baseball
"I don’t believe in god or religion." → alt.atheism
```

---

## 🔧 Technologies Used

* **Python 3**
* **scikit-learn**
* **NumPy**
* **Pandas**

---

## 📌 Future Improvements

* Add more categories from the 20 Newsgroups dataset.
* Experiment with other classifiers (SVM, Logistic Regression).
* Deploy as a simple web app with Flask/FastAPI.
* Visualize word importance using word clouds.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.




