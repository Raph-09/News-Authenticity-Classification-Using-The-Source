# News Authenticity Classification Using The Source


![fake news](https://user-images.githubusercontent.com/72034856/215819085-30a3c69c-a14f-4489-8a65-75cd9d268a09.jpg)


## UNDERSTANDING THE PROBLEM

The internet has made information more accessible than ever before, but with this convenience comes the challenge of distinguishing fact from fiction. Misinformation is rampant on the web, and it is being spread by a variety of actors, including individuals seeking personal gain, companies, politicians, and even some news media outlets. These entities propagate false information in order to sway public opinion and shape events to fit their own biases and prejudices. The manual evaluation of news for authenticity is a tedious and time-consuming process, and it is also subject to subjective bias. This makes it extremely difficult to accurately gauge the credibility of information found online.

## SOLUTION TO THE PROBLEM

Machine Learning is used to automatically predict the authenticity of news articles-it predict if news article is  false or authentic. This approach is addopted because the traditional method  of seiving through news article is tedious and impossible. The number of websites and news articles being post on the internet is growing daily and this makes it impossible for traditional tools for detected misleading information to capture all fake news.

## HOW THIS PROJECT WAS IMPLEMENTED.
The 'site_url' was combined with the news article text 'text with stopwords removed' to create a new feature called 'source' and this feature was then used to train three different machine learning algorithms to automatically predict news authenticity. The steps outlined in the methology section was carried out to prepare the data for the algorithms.

## STEPS IN PROJECT IMPLEMENTATION/METHODOLOGY

1.Import Needed Libraries

2.Reading the news articles dataset

3.Basic Information about the dataset and missing data handling

4.Exploratory Data Analysis

5.Text Preprocessing

5.1 Combining Features

5.2 Remove Punctuation

5.3 Tokenization

5.4 Stemming

5.5 Feature Encoding

5.6 Handling Imbalance of target variable

5.7 Data Segregation or splitting

5.8 Convert text to string

5.9 Vectorization using TFIDF 

6.Training machine learning models

  6.1 Adaboost Machine Learning Algorithm

  6.2 Support Vector Machine Classifier

  6.3 Passive Aggressive Classifier


## MODEL PERFORMANCE

#### Baseline model performance

#### Performance After hyperparameter optimization


## HOW TO RUN THE NOTEBOOK

#### USING GOOGLE COLAB

1. clone the repository
2. open your google colab notebook
3. click on file
4. click on open notebook
5. click on from github
6. copy link of github and paste 
7. click on search and click the notebook



#### RUN LOCALLY

1. clone this repository to your github
2. click on code
3. click on download zip
4. extract the zip file
5. open your command prompt
6. navigate to the directory where the file is stored
7. open jupyter notebook there

### TECH STACK USED

sklearn

NLTK

plotly

pandas

numpy

seaborn

matplotlib

swifter




