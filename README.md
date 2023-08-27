# BoloBot: a tourist helper chatbot - Exam Project + PW for the 2022/23 course in NLP @ UNIBO
## Marco Acerbis and Xiaotian Fan

In this repository we present our implementation of chatbot aimed to help tourists vsiting the city of Bologna. 
The bot can be configured to present information about other cities and/or topics.
This project aims to also address the language barrier faced by tourists from different countries and cultural backgrounds. 
Thus, the bot suppors three main languages: English, Italian, and Chinese.
To faciletate the usage of the chatbot an Audio Module has also been implemented, allowing users to input oral questions and receive audio answers from the chatbot.

## How to run the system

### On Colab
In the folder "Colab implementation" you can find a Python notebook that you can run on Google Colab (or on you personal pc using Jupyter).

### On your pc
After downloading this repository, you have to install the following libraries and dependencies: 
>!pip install -qU datasets pinecone-client sentence-transformers torch <br />
!pip install apache_beam <br />
!pip install ndg-httpsclient <br />
!pip install pyopenssl <br />
!pip install pyasn1 <br />

Once you are done with the installations, you need to create a free account on [Pinecone](https://www.pinecone.io/); this is needed to save your dataset.
Run "IndexCreator.py" to create a dataset of documents from Wikipedia containg information about the city of Bologna (ora change the topic to the desired one)
Now you are ready to run touristBot.py and test the chatbot yourself!
