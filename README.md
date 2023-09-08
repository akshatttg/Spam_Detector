# Spam_Detector
Spam.csv contains Ham(normal email reply to another person) & Spam messages(does looks like one of those spam advertisement email in our junk folder)
<br>
WorldCloud is used to visualize a rough estimate of the words that has the highest frequency in the data.
<br>
First Data Preprocessing is done which covers Data Cleaning 
<br>
• Converting all letters to lower/upper case
<br>
• converting all letters to lower/upper case
<br>
• removing numbers
<br>
• removing punctuation
<br>
• Removing white spaces
<br>
• removing hyperlink
<br>
• Removing stop words such as a, about, above, down, doing and the list goes on…
<br>
• Word Stemming
<br>
• Word lemmatization
<br>
Followed by Feature Extraction (converts the words to integer/floats).This can be done using CountVectorizer & TfidfVectorizer libraries.
<br>
CounntVectorizer CountVectorizer will keep a dictionary of every word and its respective id and this id will relate to the word count of this word inside this whole training set.
<br>
TfidfVectorizer. Besides of taking the word count of every words, words that often appears across multiple documents or sentences, the vectorizer will try to downscale them.
<br>
Lastly we use Naive Bayes algorithm to do the prediction.Using Naive Bayes Theorem which is every efficient in categorical data such as spam or not spam.
