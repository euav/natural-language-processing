# Weather Chatbot
This folder contains three Jupyter Notebook files for each of subtasks specified in description. All notebooks are independent and work standalone. You can open them in GitHub preview or proceed on Google Colab by clicking on the buttons below.

### `deeppavlov.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/euav/natural-language-processing/blob/master/weather-chatbot/deeppavlov.ipynb)
Weather Chatbot built on DeepPavlov framework.

### `rasa-nlu.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/euav/natural-language-processing/blob/master/weather-chatbot/rasa-nlu.ipynb)
Weather Chatbot built on RasaNLU framework.

# Description

You need to build special chatbot that can answer the most frequently asked questions. If the user's question does not relate to the set of frequently asked questions, then your chatbot should apologize and report that it does not know the answer.

You will need to make two options for chatbot: with using of the [DeepPavlov](http://docs.deeppavlov.ai/en/master/skills/faq.html) library and using the [RasaNLU](https://ajinkyat.github.io/nlp/faq-chatbot/) library.

The task for the chatbot: to answer users' questions about the weather in Novosibirsk, asked in Russian and English. Your chatbot must understand what the user asks about the weather (temperature, wind force, precipitation) for today, tomorrow or another day, and it must answer correctly. If the user asks another question (for example, «How did the Game of Thrones end?»), then the chat bot should politely refuse to answer. Actual information about the weather can be obtained, for example, like [this](https://medium.com/nexttech/how-to-use-the-openweathermap-api-with-python-c84cc7075cfc).

As a result of this homework, you will create two chat bots that solve the same problem, but one of which is implemented using DeepPavlov, and the other using RasaNLU. You should also compare two frameworks for the convenience of designing chat bots and draw conclusions.
