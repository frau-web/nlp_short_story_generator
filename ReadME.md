# Children’s Short Story Generator using NLP/Language Modelling

## Summary: 
This project was part of a group project during the NLP class in the Master of Big Data & Business Analytics at IE University, Madrid. The purpose of this project was to develop a prototyp of a Children's Short Story Generator using Natural Language Processing. We focused on exploring the technical possibilities of story generation, with a potential future goal of implementing a functioning product. We explored several different models: ngram models (4n- and 6n-) as well as a pretrained GPT2-model (medium size) and GPT2-medium and -small models finetuned with a set of children stories from the Gutenberg library. Based on this exploration, we chose a final model for text generation and implemented a user interface for the story generation. 

## Instructions. 
The latest version of the application consists of a series of jupyter notebooks, collected in this repository, and model data that is stored on a shared Google Drive folder (access permission required).

We suggest running the notebooks on Google Colab. 

The two top-level notebooks are:
- Short_story_generator (/nlp_short_story_generator/Short_story_generator.ipynb)
-	Evaluation_Pipelines (/nlp_short_story_generator/evaluation/Evaluation_Pipelines.ipynb)

Both these notebooks can be executed directly and contain the necessary steps to clone the GitHub repository and link with the Google Drive folder (if permission is given).
Using the same Open notebook method described above, the other notebooks in the repository can also be opened. This includes all the notebooks found in  
-	nlp_short_story_generator/data (EDA and model exploration and creation)
-	nlp_short_story_generator/generation (model description and encapsulation)

Although these notebooks cannot be directly executed (they are designed to serve the two top-level notebooks) they do contain extensive writeup about the models themselves.

## Other

**Coding Language:** Python

**Main Libraries used:** 
- huggingface
- fast.ai
- nltk
- Pytorch (Fine-tuning GPT2)
- Tensorflow


## Colaborators
- AlejandroAlcuaz
- alsilvah
- frau-web
- julianscholz
- paolo-gueron
- pedrolousantos
- tvg-f
