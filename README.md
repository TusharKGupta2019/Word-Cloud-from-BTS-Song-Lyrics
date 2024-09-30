# Word-Cloud-from-BTS-Song-Lyrics

I recently created a word cloud using the lyrics from BTS songs. 🎶✨

Libraries and Techniques Used:

Pandas: For data manipulation and reading the CSV file containing the lyrics.

NLTK: This library was essential for natural language processing tasks like tokenization, lemmatization, and removing stopwords.

Tokenization: Used word_tokenize to split lyrics into individual words.

Lemmatization: Employed WordNetLemmatizer to reduce words to their base forms.

Stopwords Removal: Filtered out common words that do not contribute much meaning.

Regular Expressions (re): Cleaned the lyrics by removing special characters.

WordCloud: This module helped generate the visual representation of word frequency.

Matplotlib: Used for displaying the final word cloud image.

Step-by-Step Process:

Imported the necessary libraries and read the lyrics data from a CSV file.

Cleaned the lyrics by removing null values and special characters, converting text to lowercase.

Tokenized and lemmatized the words, while also filtering out stopwords.

Finally, generated the word cloud using the cleaned text and displayed it using Matplotlib.

Creating this word cloud was a fun way to visualize BTS's lyrical themes and expressions! 🌟
