# **Credit Card Fraud Detection** 💳  

Welcome to the **Credit Card Fraud Detection Project**! 🌟  

In today’s digital economy, the security of financial transactions is paramount. With the increasing reliance on credit cards for online and offline purchases, the risk of fraudulent activities has grown exponentially. This project leverages advanced **Machine Learning algorithms** to identify and flag fraudulent credit card transactions in real-time, ensuring safer financial operations and protecting users from potential financial loss.  

By analyzing transaction patterns and anomalies in data, this project provides an intelligent and automated solution to distinguish between legitimate and fraudulent transactions. It incorporates robust classification techniques such as Logistic Regression, Decision Trees, and more, ensuring high accuracy and reliability in fraud detection.  

Whether you're a cybersecurity enthusiast, a financial analyst, or an AI practitioner, this project offers an invaluable exploration of how data science can enhance trust and security in the digital age. Dive in and be part of a mission to make financial transactions smarter and safer! 🚀  

# 🙌 Maintainers 👩‍💻 :

- [Vani Varanya](https://github.com/vanivaranya)
- [Saumya Gupta](https://github.com/ISaumya1011)

# 🙌 Collaborator 👩‍💻 :

- [Bhavya](https://github.com/its-bhavya)

---

## OVERVIEW: 

This project focuses on identifying fraudulent credit card transactions using machine learning techniques. The dataset is preprocessed by scaling numerical features and addressing class imbalance, as fraudulent transactions are rare. Logistic Regression is trained to classify transactions as fraudulent or legitimate. Model performance is evaluated using metrics like accuracy, precision, recall, and F1-score, with a focus on minimizing false negatives to reduce undetected fraud.

---

## Project Category: 
Machine Learning

---

## DATASET: 
  The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

  It contains only numeric input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. 
### Features: 

 - Features V1, V2, … V28 are the principal components obtained with PCA. 
 - The only features which have not been transformed with PCA are 'Time' and 'Amount'. 
 - Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
 - The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning.

### Target Feature: 

 - Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. 

---

## Libraries Used:
 - Scikit-learn
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn

---

## 🛠️ How to Get Started  

1. **Fork this Repository**  
   Click the **Fork** button to create your copy of this repository.  

2. **Clone the Repository**  
   ```bash  
   git clone https://github.com/GDG-IGDTUW/AI-ML-1.git  
   cd repo-name  
   ```  

3. **Install Dependencies**  
   Navigate to the project folder you're interested in.  
   For example:  
   ```bash  
   cd Sentiment-Analysis
   ```  
   Load the dataset and Install necessary Libraries

4. **Make Your Contributions**  
   - Perform EDA.
   - Train models.
   - Enhance Accuracy.
   - Add features.  
   - Test your changes.  

5. **Submit a Pull Request**  
   Push your changes and create a pull request to propose your contributions! 🎉  


---

## 🤝 Contributing Guidelines  

We ❤️ contributions! Follow these simple steps to contribute:  

1. **Browse through Issues and Choose any**  
   Browse the [Issues](#) tab and comment on the one you'd like to work on.  

2. **Clone the Repo, Make changes and Branch Out**  
   Create a new branch for your changes:  
   ```bash  
   git checkout -b feature-name  
   ```  

3. **Commit Your Work**  
   Write clear and concise commit messages:  
   ```bash  
   git commit -m "Add: Feature description"  
   ```  

4. **Push and PR**  
   Push your branch and create a pull request for review.  

---

🌟 Tips for Contributors
 - Follow the repository’s code style and structure.
 - Keep ML model training scripts well-indented and include comments.
 - Share any interesting results or insights in the pull request description.
 - If you want an issue to be assigned to you, Tag us and mention so under the issue.
 - Please be patient and Feel free to Tag the maintainer or collaborators for any queries. ❤️

---

Happy Coding and Collaborating!🚀❤️
