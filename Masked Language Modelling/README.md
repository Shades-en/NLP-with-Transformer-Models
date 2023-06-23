# Masked Language Modelling

Fine Tuning a masked language model on your own dataset with hugging face. Here imdb dataset has been chosen.

### Model
distilbert-base-uncased

you can choose any LLM such as Bert, Roberta, XLNet or distilbert.
Distilbert is chosen because it takes relatively less time to train it while retaining 97% of the performance of Bert Model.

#### Trained Model - https://drive.google.com/drive/folders/1hfAeFJj63DOIGDpd3zNx1HIaJ0vZ0SC1?usp=drive_link

### Dataset used: 
Distilbert was pretrained on English Wikipedia and BookCorpus datasets

Dataset to fine tune on -  [imdb dataset](https://huggingface.co/datasets/imdb)


### Addtional
There are two models in the drive trained with two types of data collators
* DataCollatorForLanguageModeling - Masks any token with a given probability. The tokens belonging to the same word may not always be masked together.
* DataCollatorForWholeWordMask - Masks the tokens based on the whole words with a given probability. The tokens belonging to the same word will always be masked together.
