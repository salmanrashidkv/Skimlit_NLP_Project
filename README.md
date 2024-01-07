## Skimlit NLP Project
In this project, we are replicating the deep learning model behind the 2017 paper PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts.

When it was released, the paper presented a new dataset called PubMed 200k RCT which consists of ~200,000 labelled Randomized Controlled Trial (RCT) abstracts.

The goal of the dataset was to explore the ability for NLP models to classify sentences which appear in sequential order.

#### Problem in a sentence
The number of RCT papers released is continuing to increase, those without structured abstracts can be hard to read and in turn slow down researchers moving through the literature.

#### Solution in a sentence
Create an NLP model to classify abstract sentences into the role they play (e.g. objective, methods, results, etc) to enable researchers to skim through the literature.

- Downloading a text dataset (PubMed RCT200k from GitHub)
- Writing a preprocessing function to prepare our data for modelling
- Setting up a series of modelling experiments
- Making a baseline (TF-IDF classifier)
- Deep models with different combinations of: token embeddings, character embeddings, pretrained embeddings, positional embeddings
- Building multimodal model (taking multiple types of data inputs)
- Replicating the model architecture from https://arxiv.org/abs/1612.05251
- Making predictions on PubMed abstracts from the wild
