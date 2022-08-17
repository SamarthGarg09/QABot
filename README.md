# QABot

## Description
* first used elastic search to build index of our database using[squad](https://data.deepai.org/squad2.0.zip) dataset.
* It is fast and has great advantages like it allows parallel processing.
* It is an open-domain open-book question answering model, reader-retriever model to be more specific.
* Retriever will take the question and search the related contexts using the external database.
* Then reader will get the context and question from retriever and it will then returns the start and end indexes of the answer.

> Reader model - deepset/bert-base-cased-squad2

> Retriever model 
> *  Query embedding model - facebook/dpr-question_encoder-single-nq-base
> * Passage embedding model - facebook/dpr-ctx_encoder-single-nq-base

<!-- display image -->
<img src="QA-retriever-reader.png" alt="QABot" width="1000" height="500">
