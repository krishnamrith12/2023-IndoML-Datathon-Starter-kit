# IndoML Datathon 2023: Starter Kit

## TLDR: Important dates and steps

- 👉 Register: [https://forms.gle/2d5kabsuvnUx6xX76 ](https://forms.gle/2d5kabsuvnUx6xX76 )
- 📂 Download the Data: [Check the "data" folder](https://github.com/krishnamrith12/2023-IndoML-Datathon-Starter-kit/tree/main/data)
- 🏗️ Build your model: [A quick recipe to get you upto speed](https://github.com/krishnamrith12/2023-IndoML-Datathon-Starter-kit/blob/main/README.md#a-quick-recipe-to-get-you-upto-speed)
- 🏟️ Submit your predictions at: https://codalab.lisn.upsaclay.fr/competitions/14977
- 🗓️ Competition Deadline: **12th October**
- 🏆 Win prizes worth **INR 1 Lakhs**

## 🪄 A quick recipe to get you upto speed

### Tutorial walkthrough video
- 🎥 https://www.youtube.com/watch?v=AY9qM_LFNHA
- 🎥 A more longish tutorial - https://www.youtube.com/watch?v=L3fa8Frmqro

### DIY
1. Get a model finetuned for intent detection, say on the MASSIVE dataset ➞ https://huggingface.co/models?dataset=dataset:AmazonScience%2Fmassive&sort=trending
2. Finetune  the model on our training dataset ➞  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bsantraigi/2023-IndoML-Datathon-Tutorial/blob/main/TransformerFinetune.ipynb)
3. Obtain the predictions and submit

### Data
- Data folder: https://github.com/krishnamrith12/2023-IndoML-Datathon-Starter-kit/tree/main/data
- Training data: [surprise_data.zip](https://github.com/krishnamrith12/2023-IndoML-Datathon-Starter-kit/blob/main/data/surprise_data.zip)
- Test data: [massive_test.data](https://github.com/krishnamrith12/2023-IndoML-Datathon-Starter-kit/blob/main/data/massive_test.data)
- Use your favourite text editor or IDE to see the data

### A lazy approach with prompts
1. LLM_ShortPrompt.ipynb ➞ [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bsantraigi/2023-IndoML-Datathon-Tutorial/blob/main/LLM_ShortPrompt.ipynb)
2. Obtain the predictions

## Reach out to us
- Discord https://discord.com/invite/zqp7Pma3TA
- Tutorials playlist: https://www.youtube.com/playlist?list=PLvzThk3qRkmVe1v2wRRKnQeV7BHIY5xQW
- Datathon website - https://sites.google.com/view/datathon-indoml23
- IndoML website - https://indoml.in/
- Linktree - - https://linktr.ee/datathon

<img src="images/indomlLogo.jpg">


## Notebooks

1. EDA.ipynb ➞ [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bsantraigi/2023-IndoML-Datathon-Tutorial/blob/main/EDA.ipynb)

2. TransformerFinetune.ipynb ➞ [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bsantraigi/2023-IndoML-Datathon-Tutorial/blob/main/TransformerFinetune.ipynb)

3. LLM_ShortPrompt.ipynb ➞ [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bsantraigi/2023-IndoML-Datathon-Tutorial/blob/main/LLM_ShortPrompt.ipynb)

## Tutorial

In the online tutorial we will go over the notebooks of this repo. We focus on the [AmazonScience/MASSIVE](https://huggingface.co/datasets/AmazonScience/massive) multilingual intent-detection. 

There are few different parts to the tutorial:

1. EDA.ipynb: We first explore the dataset a bit to understand the task and various stats about the data. We also get to see how to use the `datasets` library from HuggingFace, what metadata information is available, and how to apply preprocessing to the data.
2. FinetuneTransformer.ipynb: We then finetune a transformer model on the dataset. We use the `Trainer` class from HuggingFace to do this. 
3. LLM_PromptEngineering.ipynb: We then explore the use of LLMs for intent detection. We explore an in-context learning method to solve the task using a instruction-finetuned large-language model (LLM), without any finetuning.

There are also a few other bonus scripts available that showcases the use of other advanced techniques like parameter efficient tuning and low-rank adaptation methods. These methods will be useful for the datathon, to tackle the few-shot challenge in later phases and running on GPU devices available through Colab.

## Where to get free GPU resources?

Best options are Kaggle Notebooks and Google Colab.

## Other Links

##IndoML-2023 #Datathon 

based on materials from the tutorial by [@bsantraigi](https://github.com/bsantraigi/2023-IndoML-Datathon-Tutorial), titled Intent Detection: From Sesame Street to LLMs. 
Tutorial video available here: https://www.youtube.com/watch?v=L3fa8Frmqro


* Nice blog about training very large models (Falcon-7b!) on Colab: [The Falcon has landed in the Hugging Face ecosystem](https://huggingface.co/blog/falcon)
    * Colab Link: [Finetuning Falcon-7b](https://colab.research.google.com/drive/1BiQiw31DT7-cDp1-0ySXvvhzqomTdI-o?usp=sharing)

