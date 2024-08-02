![Repository banner](media/yesterday_banner.jpg)

## 🧠🧹 Yesterday: Machine Unlearning

Welcome to the "Yesterday" project, an introduction to the concept of machine unlearning. This repository contains work aimed at understanding and implementing methods to make machine learning models "forget" specific information. The project includes two main components:

1. **Forgetting the Digit '6' in an MNIST Classifier**
2. **Forgetting the Beatles from a Pretrained GPT-2 Model**

Motivated by the movie [Yesterday](https://en.wikipedia.org/wiki/Yesterday_(2019_film)) where the lead character wakes up in a Beatles-less world.

### Overview

#### 1. MNIST Classifier

This component deals with a neural network trained on the MNIST dataset, a collection of handwritten digits. The goal is to make the model forget how to recognize the digit '6' without retraining the entire network from scratch.

- **Notebook:** `Machine_Unlearning_MNIST.ipynb`
- **Description:** This Jupyter notebook demonstrates techniques for unlearning the digit '6' from the classifier by modifying the model's weights and/or training data.

#### 2. GPT-2 Language Model

This component focuses on a text generation model, GPT-2. The objective is to remove knowledge of "The Beatles" from the model's responses, effectively making it forget any associations or references related to the band.

- **Notebook:** `Machine_Unlearning_LM.ipynb`
- **Description:** This Jupyter notebook provides methods to unlearn specific content from the pretrained GPT-2 model. It includes approaches for filtering or modifying the model’s responses to ensure it no longer includes information about "The Beatles".

---

### How to try it

#### On Google Colab:

1. Open the notebooks on Google Colab:
   - [MNIST Classifier](https://githubtocolab.com/mich1803/Yesterday-Machine-Unlearning/blob/main/Machine_Unlearning_MNIST.ipynb)
   - [Language Model](https://githubtocolab.com/mich1803/Yesterday-Machine-Unlearning/blob/main/Machine_Unlearning_LM.ipynb)

#### On local:

1. Clone this repository.
2. Create a virtual environment.
3. Install the requirements with `pip install -r requirements.txt` in your virtual environment.
4. Open the notebooks in your IDE.



