git clone https://github.com/alifpandanhifebrio/chatbot.git
cd chatbot
python3 -m venv venv
venv/Scripts/activate

Install Library
$ (venv) pip install Flask torch torchvision nltk

Install nltk package
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
