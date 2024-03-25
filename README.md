# Large Rodent (Paca, Agouti, and Capybara) Classification

In this notebook, the concepts and codes from Chapter 2 of the book _Deep Learning for Coders with fastai and PyTorch_ are applied to build a large rodent (Paca, Agouti and Capybara) classifier.

This notebook applies concepts and code from Chapter 2 of _Deep Learning for Coders with fastai and PyTorch_ to build a classifier for three large South American rodents: pacas, agoutis, and capybaras.

Here's an overview of the steps involved:

**Dataset creation**

* Gather images of each rodent from online resources.
* Use a `DataLoader` to manage and split the data for training and validation.
* Apply data augmentation techniques to improve the model.

**Model training**
* Leverage a pre-trained model for efficient learning.
* Utilize the Fastai cleaner GUI for data cleaning.

**Web App development**
* Create a basic web app prototype to showcase the model's predictions.

Despite the limited dataset size (approximately 150 per rodent), the model demonstrates promissing performance.

**Interesting Facts about Pacas, Agoutis, and Capybaras:**

* These herbivorous rodents typically dwell near water sources.
* They share similar lifespans, ranging from 14 to 16 years.
* While pacas are solitary animals, agoutis live in small groups, and capybaras form large social groups.
* All three species contribute to seed dispersal by burying and forgetting food sources.

*Try it yourself here:*
[![Hugging Face space](https://huggingface.co/front/assets/huggingface_logo.svg)](https://huggingface.co/spaces/vechism/rodents)
