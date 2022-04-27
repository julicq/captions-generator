# captions-generator

A Captions generator for pictures which could be shown to the ML model and get result in command line.

Dataset used for training - Flicker8k_Dataset

Download
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip
and extract to the root folder with other files.

Launch order:
0. 1.py - check libs. TF should be installed for Keras
1. extraction.py - prepare photo and text data
2. vocabulary.py - create vocab
3. load_data.py - lead data
4. training.py - train model using batches - optimized for small stations and laptops with less than 16GB RAM
5. evaluate.py - evaluate model
6. tokenizer.py - create word tokens
7. generator_final.py
