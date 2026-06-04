# Large PDF text summarization

*Personal project*

## Project presentation

This Project is based on trying to summarize academic texts with around 4000 characters into summaries of around 1000 characters.  



## Data

The data used in this project was obtained through the https://www.drivendata.org/ website, especifically the https://www.drivendata.org/competitions/297/whats-up-docs/ competition.



## Methodology

* Data preprocessing. Since text dimensions are very large and won`t fit the model inputs without losing a lot of context I resorted to context chunking and then keeping the top chunks that are more relevant to the provided summary. The relevancy is calculated through calculating the embeddings of each chunk and each summary and calculating the cosine similarity of both vectors.
* Model implementation and validation. For the implementation of this model, I finetuned, using PeFT, the pretrained \*\*google/flan-t5-large\*\* model
* Review of model performance using Rouge-score metrics

## Tools

`Python`, `Pandas`, `Transformers`, `scikit-learn`, `torch`, `HuggingFace`

## Results



## Author

*Victor López*
[LinkedIn](https://linkedin.com/in/victor-lopez-lopez) | [Email](mailto:lopezzvictor21@gmail.com)

