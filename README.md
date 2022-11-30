# Sentiment Analysis using NLP
This project was part of my Research Assistant at my University. I was given around 14,209 pdf files where I had to perform sentiment analysis using natural language processing in python upon converting the pdf files to txt files.

STEP 1

Converting all the pdf files to txt file. The PDF_To_TXT.ipynb file contains the code for converting the pdf files to txt file simultaneously. I have used python and regex function for the same.

STEP 2

While performing sentiment analysis of any text file it is important to remove all the redundant data.The data which holds no value in your analysis. By redundant data I mean stop words,etc. I wrote a code using nltk library which helped me in removing those unwanted words. The code Stop_Words.ipynb contains the code for stop words removal.

STEP 3 

Extracting Bigrams and Trigrams from a text file. Bigrams are the words which has two words in it while trigrams are words which has three and they carry some meaning in it. They both help in predicting the content of your data. The file Bi_trigrams.ipynb has the code to extract both bigrams and trigrams. The code also calculates the frequency of bigrams and trigrams.

STEP 4 

Finally the most important part of this project was performing Sentiment Analysis on those files. I implemented the sentiment analysis in python using nltk library based on Bigrams and Trigrams. The sentiment analysis is based on polarity and subjectivity. By polarity means how positive or negative the data is and by subjectivity means is the data being objective or subjective. The file Sentiment.ipynb contains the code for this analysis.
