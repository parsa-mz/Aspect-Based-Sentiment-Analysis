## Aspect-Based Sentiment Analysis



## Introduction

The goal of this homework is to train a model to do aspect-based sentiment analysis. The model will be trained on a dataset of sentences and their corresponding aspect and sentiment. The model will then be tested on a test set of sentences and their corresponding aspect. The model will predict the sentiment of the aspect in the sentence. The model will be evaluated on the accuracy of the predictions.


## Requirements

The project uses [Python 3.10](https://www.python.org/downloads) which has some linting defaults which may cause import
errors if using python < 3.10 and [PyTorch](https://pytorch.org/)

The requirements can be installed using the following command:

```bash
    # create a virtual environment
    py -m venv env
    # windows only
    env\Scripts\activate
    # linux or mac
    source env/bin/activate
    
    # install requirements
    pip install -r requirements.txt
```

For dataset we're using Semeval 2014 dataset which can be downloaded from [here](https://www.kaggle.com/ankurzing/sentiment-analysis-for-financial-news/data?select=semeval2014-task9-testdata.txt)

Also the dataset can be mounted from google drive as well. The code is written in a way that it can be used with both options.


## Running the code

The code has been written in jupyter notebook so that each part can be run individually and test different senarios and variables along the way. The notebook can also be imported into colab as well if you prefer working in the cloud GPU.



## Project Structure

The project is structured as follows:

```bash
    .
    ├── /data
    ├── /result
    ├── README.md
    ├── requirements.txt
    └── notebook.ipynb
```

The `data` folder contains the data files for the project. The `notebook` is a jupyter notebook which contains the code
for the project. 


## Model

For this assignment, I've used pre-trained BERT model and fine-tuned it for the Aspect-Based Sentiment Analysis task. The model is trained on the Semeval 2014 dataset and tested on the test set of the same dataset. The model is evaluated on the accuracy of the predictions.



## Authors

Parsa Mazaheri, December 2022