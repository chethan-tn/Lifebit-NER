# Lifebit-NER
Chethan Navanitha - Lifebit Technical Challenge Repo

# Dependency installation
In this project open-source NLP library SpaCy is used in the context for adopting Transfer Learning. By using the ppre-trained language madel. And only the nlp model framework (blank model) is used to achieve upstream tasks. 

Step-1: Install Spacy

pip install 'spacy<3.1.0,>=3.0.0' --force-reinstall

Step-2: Install pre-trained Transformer based Spacy NLP pipeline

python3 -m spacy download en_core_web_trf

Step-3: Check if the installed packages are compatiple

python3 -m spacy validate


# NER Model
1. NER Model based on Pre-Trained Transformer based SpaCy moddel
2. NER Model based on blank english Spacy Model


Open the notebooks and restart and run all. However, to re-train the model follow the instructions in notebook

Make sure all the files/folders in the repo is are present 

