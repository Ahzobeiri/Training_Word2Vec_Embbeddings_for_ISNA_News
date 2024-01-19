# Training_Word2Vec_Embbeddings_for_ISNA_News
In this repository, I trained the embedding of words (Word2Vec representation) to evaluate the similarity of words and gain insight into Persian words with close meanings, using the ISNA news corpus, "PERSICA", as the dataset. The "PERSICA" corpus includes news ID, title, text, date, publication time, and the news label. It can be utilized for various NLP tasks like news classification, topic discovery and classification, category classification, and many more procedures.
The dataset is an open-source corpus that can be downloaded from the address (https://sourceforge.net/projects/persica/files/persica.csv/download). In the Notebook code I provided, I wrote step-by-step procedures that should be done to train word vectors (Word2Vec). These steps are as follows:
The body of this Notebook code which was written in the Colab environment, consists of the following 7 headings:

Step 1️⃣ : In the first step, I defined the functions "read_isna_content()" and "read_isna_content_to_list()"to read the text content of all news articles in the corpus. The first function returns a string containing the content of all news articles in the ISNA corpus and the second one returns a list of the first one. 🕐

Step 2️⃣: In the second step,  by defining the function called "normalize", the string of all news text will be read, and the output which is also a string will be returned. This function has to unify the different codings of a Persian letter (like "ئ/ي'" to "ی" and "ك" to "ک"). For normalization in this function, I do not remove anything from the text (for example, I don't remove the Latin letters) but the basic point is that the output text of the function is in a way that each unit is 2 units apart from the other units. Additionally, the function converts extra spaces to single spaces.🕑

Step 3️⃣ : Next, in the 3rd step, I divided the whole corpus body into its constituent sentences. For identification of the sentence boundary, I used the "re.split" method with punctuation marks such as ":.;?!". For this step, I defined a function called segment_corpus_. The input of this function is a string (that is, the whole corpus as a string) and its output is a list of sentences of the body.🕒

Step 4️⃣ : In the 4th step, I divided the whole corpus body into its constituent sentences. For identification of the sentence boundary, I used the "re.split" method with punctuation marks such as ":.;?!". For this step, I defined a function called segment_corpus_. The input of this function is a string (that is, the whole corpus as a string) and its output is a list of sentences of the body.🕓




.
