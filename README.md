# sentiment-analysis-bert
Sentiment140 Twitter dataset sentiment analysis model with BERT (Bidirectional Encoder Representations from Transformers). The polarity of the tweets is classified in this project. 
0 = negative, 4 = positive

See details about the dataset: http://help.sentiment140.com/for-students 

Huggingface pytorch implementation for a lot of NLP tasks. In this project, [BertForSequenceClassification](https://huggingface.co/transformers/model_doc/bert.html#bertforsequenceclassification) is used
from transformers library. Transformers library 4.3.2 is used. You can install this version of the library: ``` pip install transformers==4.3.2 ```

[Colab](https://colab.research.google.com/) is used for fine tuning the pretrained BERT model. 

Read this paper about BERT -> [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)


## Results:

                      precision    recall  f1-score   support

            Negative      0.82      0.81      0.82      3749

            Positive      0.81      0.82      0.82      3752


            accuracy                           0.82      7501

           macro avg       0.82      0.82      0.82      7501

        weighted avg       0.82      0.82      0.82      7501
