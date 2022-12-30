# Awesome NLP benchmarks for intent-based chatbots

List of benchmarks to evaluate the quality of your intent matching and entity recognition chatbot components. Given the myriad of NLP/NLP libraries to build your own chatbot ([DialogFlow](https://cloud.google.com/dialogflow), [Amazon Lex](https://aws.amazon.com/lex/), [Rasa](https://github.com/RasaHQ/), [NLP.js](https://github.com/axa-group/nlp.js/), [Xatkit](https://github.com/xatkit-bot-platform), ...), it's important to be able to have some datasets we could use to benchmark them. 

To evaluate the quality of intent-matching and entity recognition components, we cannot just use raw NLP datasets. We need datasets that include:
- The user utterance
- The intent that should be matched given that utterance 
- The list of entities that should be identified in that utterance 

Obviously, even better if the dataset already comes with different sets of data for training, testing and validation so that different authors/vendors can more precisely replicate and report the evaluation results they get when evaluating a given library.

## Datasets 

- [**NLU Evaluation Corpora**](https://github.com/sebischair/NLU-Evaluation-Corpora). Three corpora which can be used for evaluating chatbots or other conversational interfaces. Two of the corpora were extracted from StackExchange, one from a Telegram chatbot. For instance, these corpora have been used in [this benchmark](https://github.com/axa-group/nlp.js/blob/master/docs/v3/benchmarking.md).

https://www.kaggle.com/datasets/joydeb28/nlp-benchmarking-data-for-intent-and-entity


https://github.com/alexa/massive


## Papers

Research works discussing, proposing or comparing NLP benchmarks:

- [Benchmarking Commercial Intent Detection Services with Practice-Driven Evaluations](https://aclanthology.org/2021.naacl-industry.38.pdf)



## Additional Links

- Datasets for other NLP tasks: [https://github.com/niderhoff/nlp-datasets](https://github.com/niderhoff/nlp-datasets)
- Great post to get you started on the fascinating world of [building your own chatbot platform](https://jseijas.medium.com/how-to-build-your-own-nlp-for-chatbots-9b4c08eb03a9)


## Contributing
Feel free to open an issue or submit a pull request with any NLP dataset for chatbots that we may be missing (thanks!).
