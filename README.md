# Training_Word2Vec_Embbeddings_for_ISNA_News
In this repository, I trained the embedding of words (Word2Vec representation) to evaluate the similarity of word embeddings and get an intuition about Persian close-meaning words, using the ISNA news corpus, "PERSICA", as the dataset. The "PERSICA" corpus includes news ID, title, text, date, publication time, and the news label. It can be used for several NLP tasks like news classification, topic discovery and classification, category classification, and many more procedures.
The dataset is an open-source corpus that can be downloaded from the address (https://sourceforge.net/projects/persica/files/persica.csv/download). In the Notebook code I provided, I wrote step-by-step procedures that should be done to train word vectors (Word2Vec). These steps are as follows:
The body of this Notebook code which was written in the Colab environment, consists of the following 7 headings:

Step 1️⃣ : In the first step, by defining the functions "read_isna_content()" and "read_isna_content_to_list()", the text content of all corpus news has been read, and a list of all ISNA corpus news is returned as the output of the function.🕐

Step 2️⃣: In the Second step,  by defining the function called "normalize", the string of all news text will be read, and the output which is also a string will be returned. This function has to unify the different codings of a Persian letter (like "ئ/ی/ ..." to "ی", "K" to "K" and so on) and perform normalization. For normalization in this exercise, better Do not remove anything from the text, for example, you don't need to remove the Latin letters, but the basic point is: we want each unit to be 2 units apart from the other units, so make sure before and after every word, every number and every symbol. Insert space notation Don't forget to convert extra spaces to single spaces at the end.


.
