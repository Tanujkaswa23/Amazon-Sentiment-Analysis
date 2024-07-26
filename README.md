# Amazon-Sentiment-Analysis
This project aims to classify customer reviews of Amazon products into positive and negative sentiments. We can gain insights into customer opinions and satisfaction levels regarding various products by analyzing these reviews.
## Motivation and Objectives
The primary motivation for this project is to help Amazon and other stakeholders understand customer sentiment towards their products. This understanding can inform marketing strategies, product improvements, and customer service enhancements. By identifying positive and negative review trends, companies can better address customer concerns, capitalize on successful product features, and improve overall customer satisfaction. The project also serves as a practical application of natural language processing (NLP) techniques and sentiment analysis, showcasing the power of data analytics in extracting valuable insights from textual data.

## Project Structure
The project is structured as follows:

### 1. Importing Libraries and Data

	Libraries: NumPy, Pandas, Matplotlib, Seaborn, NLTK, WordCloud.
	Data: Importing and exploring the dataset containing customer reviews (df = pd.read_csv('7817_1.csv')).

### 2. Data Exploration and Cleaning

	Checking for null values and data types (df.info(), df.isnull().sum()).
	Dropping irrelevant columns and extracting useful features such as review date (df.drop([...], axis=1, inplace=True)).

### 3. Data Preprocessing

	Tokenization, stopwords removal, and text cleaning using NLTK and regular expressions.
	Custom sentiment dictionary and score adjustment (sid.lexicon.update(word_dict)).

### 4. Sentiment Analysis

	Using VADER SentimentIntensityAnalyzer to calculate sentiment scores for each review.
	Categorizing sentiment scores into positive, neutral, or negative.

### 5. Results and Visualization

	Grouping and visualizing sentiment data over time to observe trends.
	Displaying final sentiment classifications and performing further analysis on specific categories.

## Technologies and Libraries Used
Programming Language: Python
Libraries:
	Data Manipulation: NumPy, Pandas
	Data Visualization: Matplotlib, Seaborn, WordCloud
	Natural Language Processing: NLTK
	Text Preprocessing: re, string

## Contributions and Acknowledgements
This project was developed independently, but it relies on publicly available data and open-source libraries. Special thanks to the developers and maintainers of the libraries used.
