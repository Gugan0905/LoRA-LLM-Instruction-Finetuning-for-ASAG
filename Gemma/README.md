# Gemma

All libraries, params, training and evaluation methods can be found in the 'NLP_Project_Gemma_Mistral.ipynb' notebook.
The Gemma 2b model was the only model we were able to succesfully run, and certain experiment variations include trying out an f1 loss during training that could be better for Sequence Classification tasks.

The saved model files can be found at the following hugging face links.
- https://huggingface.co/adhi29/adapter-gemma-2b-v3.0-lora-answer-evaluator
- https://huggingface.co/adhi29/adapter-gemma-2b-lora-answer-evaluator
- https://huggingface.co/adhi29/adapter-gemma-2b-v2.0-lora-answer-evaluator-f1loss
- https://huggingface.co/adhi29/adapter-gemma-2b-v2.0-lora-answer-evaluator-f1loss

Other Mistal training files can also be found here
- https://huggingface.co/adhi29/mistral-lora-token-classification
- https://huggingface.co/adhi29/mistral-7b-lora-answer-evaluator

Be sure to install the requirements by running the following code

``` pip install -r gemma_requirements.txt ```

Before running the code be sure to have the dataset in this directory with the "data.csv" filename