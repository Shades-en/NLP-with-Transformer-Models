
# Named Entity Recognition

Named entity recognition with hugging face classifying Person, Organisation and Location.

### Dataset used: 
[CoNLL-2003 dataset](https://huggingface.co/datasets/conll2003)


### Labels:
* 'O': 0, 
* 'B-PER': 1
* 'I-PER': 2 
* 'B-ORG': 3 
* 'I-ORG': 4 
* 'B-LOC': 5 
* 'I-LOC': 6 
* 'B-MISC': 7 
* 'I-MISC': 8

### Model:
https://drive.google.com/drive/folders/1zzXdMWJMFfCfLb52xjg5YF1yTmJpOmyw?usp=drive_link

### Addtional
Although the notebook contains modeling for NER but the dataset also contains tags for chunking and Part-of-speech tagging (POS). So one can train the model on those as well following similar steps.
