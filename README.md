# Project Overview

The primary objective obehind this lab is to get familiar with NLP language models
using Pytorch library.


## Notebooks Description

### Lab_4_1.ipynb

##### Classification Regression:

This notebook focuses on collecting and analyzing Arabic text data from several websites using scraping libraries such as Scrapy and BeautifulSoup. The collected texts will be evaluated based on their relevance to a specific topic, with scores ranging from 0 to 10. Once the data is gathered, it will undergo preprocessing through an NLP pipeline that includes tokenization, stemming, lemmatization, stop word removal, and discretization. Subsequently, various recurrent neural network (RNN) models, including RNN, Bidirectional RNN, GRU, and LSTM, will be trained, with hyperparameter tuning to optimize performance. Finally, the models will be evaluated using standard metrics like accuracy, precision, recall, and F1 score, as well as specialized metrics such as the BLEU score, to determine the most effective architecture for processing Arabic text data.### Lab_4_2.ipynb
##### Transformer (Text generation):

This notebook involves installing the PyTorch-Transformers library and loading the pre-trained GPT-2 model. The main steps include fine-tuning the GPT-2 model on a customized dataset, which can be generated as needed. After fine-tuning, the model will be used to generate new paragraphs based on a given sentence, demonstrating its ability to produce coherent and contextually relevant text.### Lab_4_1.ipynb
##### BERT:

This notebook focuses on leveraging the pre-trained BERT model (bert-base-uncased) for text analysis using a dataset from Amazon product reviews. The steps include establishing the BERT model, preparing the data, and adapting the BERT embedding layer. Following data preparation, the model will be fine-tuned and trained with optimal hyperparameters to achieve high efficiency. The model's performance will be evaluated using standard metrics such as accuracy, loss, and F1 score, as well as specialized metrics like BLEU score and BERTScore.
## Installation

To run these notebooks:
1. Clone this repository.
2. Ensure that Python 3 and Jupyter are installed on your machine.
3. About Dataset:
   - the link to load the second one : https://www.kaggle.com/code/jocelyndumlao/autollm-gpt2-ai-generated-text/input

   - the link to load the third one :https://nijianmo.github.io/amazon/index.html.

## Contributing

Contributions to enhance or extend the functionality of these notebooks are welcome, especially in the areas of text analytics using pre-trained models. Please feel free to fork the repository, make your changes, and submit a pull request.
