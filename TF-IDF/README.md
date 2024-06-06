# Term Frequency Inverse Document Frequency
<p>
    Term Frequency - How often the word appears in a document divided by the total number of words. <br />
    TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document)
    Inverse document frequency - How unique or rare a word is in all the documents. <br />
    IDF(t) = log_e(Total number of documents / Number of documents with term t in it) <br /><br />
    The IDF helps in reducing the weight of commonly occurring words and increasing the weight of rare words
    TF-IDF weight is the product of TF(t) x IDF(t)
</p>