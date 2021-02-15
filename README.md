# Movie-Q-A-chatbot
Ask questions and get answers.

#CRC 
https://echeung.me/crcmaker/

## Libraries used:

#### Pytorch
#### Gensim
#### Spacy
#### HuggingFace transformers
#### wikipedia API





## classes

### QuestionProcessor
Processes the question and keeps only essential parts.

### ContextRetriever
Processes the text from wikipedia API and gives text which is required for the model to answer question.

### AnswerRetriever
Instantiates the model and finds answer.







## Functions

### search_article
facilitates for searching the article in wikipedia

### download_article
downloads the article and returns content

### ask_question
takes question and finds the answer using above classes and returns answer and time taken to answer.
