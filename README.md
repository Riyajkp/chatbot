# chatbot

LLMs differ from each other in how they are trained. 

    Text generation:
    If you need a general-purpose text generation model, consider using the GPT-2 or GPT-3 models. They are known for their impressive language generation capabilities.
    Example: You want to build a chatbot that generates creative and coherent responses to user input.

    Sentiment analysis:
    For sentiment analysis tasks, models like BERT or RoBERTa are popular choices. They are trained to understand the sentiment and emotional tone of text.
    Example: You want to analyze customer feedback and determine whether it is positive or negative.

    Named entity recognition:
    LLMs such as BERT, GPT-2, or RoBERTa can be used for Named Entity Recognition (NER) tasks. They perform well in understanding and extracting entities like person names, locations, organizations, etc.
    Example: You want to build a system that extracts names of people and places from a given text.

    Question answering:
    Models like BERT, GPT-2, or XLNet can be effective for question-answering tasks. They can comprehend questions and provide accurate answers based on the given context.
    Example: You want to build a chatbot that can answer factual questions from a given set of documents.

    Language translation:
    For language translation tasks, you can consider models like MarianMT or T5. They are designed specifically for translating text between different languages.
    Example: You want to build a language translation tool that translates English text to French.


Will be using facebook/blenderbot-400M-distill because it has an open-source license and runs relatively fast.

To create a Python virtual environment and install the necessary libraries.
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env
python3 -m pip install transformers==4.30.2 torch
