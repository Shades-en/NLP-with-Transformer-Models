
# Multilingual Summarization

Training a bilingual model for summarization in English and Spanish. The outcome is that you’ll have a model that can summarize customer reviews. These summaries are concise because they’re learned from the titles that customers provide in their product reviews. 

### Model
google/mt5-small

Other Models you can use for the above purpose are google/mt5-base, facebook/mbart-large-50.

#### Trained Model - https://drive.google.com/drive/folders/18pEoy-zG3ufxd9qX0pJ9QZSTRQKDtsI_?usp=drive_link

### Dataset used
Dataset to fine tune on -  [amazon_reviews_multi](https://huggingface.co/datasets/amazon_reviews_multi)


### Addtional
The dataset comprises of 4,00,000 reviews for both English and Spanish combined but due to limitations of computing resources the model is trained only on 10000 reviews, yet performs good.

