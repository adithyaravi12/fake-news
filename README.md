
# Differentiating Fake and Real News

A model is trained to recognize false and true news from the provided training dataset using Passive Aggressive Classifier from scikit learn, and predictions are made on the test dataset.
## Procedure

	1. Import dependencies
    2. Read tehe dataset and store it as a dataframe
    3. Store the labels from the dataset as an individual dataframe named labels
    4. Now, using train_test_split from sklearn, split the test and training datasets using the 'text' and 'labels' columns only
    5. Since this is an information retreival problem,  term frequency-inverse document frequency(tfidf) is used with the stop_words in English language and the model is trained.
    6. The PAC is now fitted on the training dataset and allowed to train for 50 iterations
    7. Predictions are made and the confusion matrix is displayed


## Run Locally

Clone the project

```bash
  git clone https://github.com/adithyaravi12/code-scanner
```

Go to the project directory

```bash
  cd code-scanner
```

Install necessary dependencies 
```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Screenshots

![App Screenshot](https://github.com/adithyaravi12/fake-news/blob/main/fake_news_output.png)

## 🔗 Links
[![My Portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](http://adithyaravi12.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adithya-ravi-707443126/)



## Documentation

- [Dataset](https://www.kaggle.com/datasets/hassanamin/textdb3?resource=download)






