# Email Data Preprocessing and Feature Extraction

## Step 1: Reading and Exploring Email Data  
- Load the email dataset into a pandas DataFrame.  
- Display the top 5 rows of the dataset to examine its structure.  
- Describe the data to get an overview of its statistical properties.

---

## Step 2: Data Cleaning  
- **Remove duplicate emails** (if any) from the dataset.  
- **Handle missing values** (if any).  
- Write a function to **clean the text data** by removing special characters, HTML tags, and other irrelevant information.  
- Apply the above cleaning function to the email text.  
- Display the first five emails from both raw and cleaned datasets to compare the changes.

---

## Step 3: Emoji Removal  
- Write a function to **remove emojis** from the email text.  
- Apply the emoji removal function to the email body text.

---

## Step 4: Stemming and Lemmatization  
- Apply **stemming** using NLTK or another stemming library.  
- Use **NLTK** or **spaCy** to perform **lemmatization** on the email text.  
- Implement **lemmatization using spaCy** and compare the results with the NLTK-based lemmatization.

---

## Step 5: Stop Word Removal  
- Remove common **English stop words** from the email text using a custom function (Create a list of possible stop words and remove them).  
- Use **NLTK** to remove stop words from the emails.

---

## Step 6: Tokenization  
- Tokenize the cleaned and preprocessed text into words.  
- Create a new column in the DataFrame to store the tokenized text.

---

## Step 7: Feature Extraction using TF-IDF  
- Write a custom function to calculate **TF-IDF vectors** for the email text.  
- Use a built-in function to extract **TF-IDF** representations of the email text.

---

## Step 8: Feature Extraction using Bag of Words (BoW)  
- **Explain the Bag of Words (BoW)** approach.  
- Use **scikit-learn** to create **BoW** representations of the email text.  
- Compare **TF-IDF** and **BoW** representations for a specific email and discuss the differences.

---
