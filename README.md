# spam-mail-detection

Spam mail detection is a technique used to automatically identify and filter unwanted or unsolicited emails. It employs various methods, including statistical analysis, machine learning, and natural language processing, to analyze email content, sender information, and other characteristics to determine if an email is spam. This helps in preventing spam from reaching users' inboxes, improving email security, and protecting against phishing attacks.

---

## Features
  - Data preprocessing to handle null values and label encoding.
  - Text feature extraction using TF-IDF Vectorization.
  - Model training and evaluation using Logistic Regression.
  - High accuracy on both training (~96.77%) and test (~96.68%) datasets.
  - A predictive system to classify new email messages as spam or ham.

---
 ## Technologies used

 - **Python**
 - **Numpy**
 - **Pandas**
 - **Scikit-learn**

   ---
   ### Installation
   1.Clone he Repository
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
   2.Create a Virtual Environment (Optional but Recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

   3. Install Required Packages
   ```bash
   pip install -r requirements.txt
   ```
   4.Run the Code
   Run in a Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
  Open spam_ham_classifier.ipynb to execute and analyze the steps.

  Or Run the Python Script Directly:
  ```bash
  python main.py
  ```

---

## License
 This project is licensed under the [MIT License](license). Feel free to use, modify, and distribute this project as per the license terms.


   
