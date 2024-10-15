# TEXT CLASSIFICATION
Text classification is important in many aspects of natural language processing (NLP). Every day, a 
massive volume of unstructured text data is gathered from numerous sources, including articles, tweets, 
and posts on social media. It is possible to examine these unstructured messages and extract information. 
Text classification can be used for several natural language processing (NLP) applications, including 
subject identification, sentiment analysis, and prediction.
During this task, a binary classification was implemented. Binary classification is a type of text classification which 
intendsto classify text into two classes. In this case, this task determines whether some news isfake, or some newsis
true based on its content.
![image](https://github.com/user-attachments/assets/e230abce-d4f4-463f-98f2-2870c3f6860c)
When implementing a text classification, there are several models that can be used. For this task, three 
embedding models will be trained using the merged fake news and true news dataset. The three embedding 
models include NNLM-en-dim50/2, NNLM-en-dim50-with-normalization/2 and NNLM-en-dim128-withnormalization/2. All the three models have the capacity to convert sentences into embeddings vector which 
is the best way to represent the text.
The Fake and True dataset, which contains different news scraped from different article will be processed
by removing stop words, new lines, words containing numbers, punctuations and text in square brackets,
making the text lowercase, and some other preprocessing steps that is required to get the dataset ready for 
training.
