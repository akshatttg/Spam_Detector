# Spam_Detector
Spam.csv contains Ham(normal email reply to another person) & Spam messages(does looks like one of those spam advertisement email in our junk folder)
WorldCloud is used to visualize a rough estimate of the words that has the highest frequency in the data.
First Data Preprocessing is done which covers Data Cleaning 
• Converting all letters to lower/upper case
• converting all letters to lower/upper case
• removing numbers
• removing punctuation
• Removing white spaces
• removing hyperlink
• Removing stop words such as a, about, above, down, doing and the list goes on…
• Word Stemming
• Word lemmatization
Followed by Feature Extraction (converts the words to integer/floats).This can be done using CountVectorizer & TfidfVectorizer libraries.
CounntVectorizer CountVectorizer will keep a dictionary of every word and its respective id and this id will relate to the word count of this word inside this whole training set.
TfidfVectorizer. Besides of taking the word count of every words, words that often appears across multiple documents or sentences, the vectorizer will try to downscale them.
Lastly we use Naive Bayes algorithm to do the prediction.Using Naive Bayes Theorem which is every efficient in categorical data such as spam or not spam.
