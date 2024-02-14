# Generating synthetic data with LLM-s for training a downstream model

Example repository of generating and annotating synthetic texts and using them to train a downstream model. 
[generating_and_annotating_example.ipynb](generating_and_annotating_example.ipynb) contains an example workflow of how we generate the synthetic texts using our custom GPT-2 model and then use Azure API's LLM to annotate it, creating training data.
[training_annotated_texts_example.ipynb](training_annotated_texts_example.ipynb) contains an example workflow of training the downstream model and evaluating it on the test data.
