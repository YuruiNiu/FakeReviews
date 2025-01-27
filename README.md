# This GitHub repository is for academic purposes only. The materials uploaded here is for a course project on Applied Data Science.
# Creating and Detecting Fake Reviews

This repository contains the code from:

>**Creating and Detecting Fake Reviews of Online Products**
>*Salminen, J., Kandpal, C., Kamel, A. M., Jung, S.-G., & Jansen, B. J. (2021). Creating and Detecting Fake Reviews of Online Products. Journal of Retailing and Consumer Services.*

>Link to paper: https://www.sciencedirect.com/science/article/pii/S0969698921003374

> **Abstract:** *Customers increasingly rely on reviews for product information. However, the usefulness of online reviews is impeded by fake reviews that give an untruthful picture of product quality. Therefore, detection of fake reviews is needed. Unfortunately, so far, automatic detection has only had partial success in this challenging task. In this research, we address the creation and detection of fake reviews. First, we experiment with two language models, ULMFiT and GPT-2, to generate fake product reviews based on an Amazon e-commerce dataset. Using the better model, GPT-2, we create a dataset for a classification task of fake review detection. We show that a machine classifier can accomplish this goal near-perfectly, whereas human raters exhibit significantly lower accuracy and agreement than the tested algorithms. The model was also effective on detected human generated fake reviews. The results imply that, while fake review detection is challenging for humans, “machines can fight machines” in the task of detecting fake reviews. Our findings have implications for consumer protection, defense of firms from unfair competition, and responsibility of review platforms.*

>**Keywords:** *fake reviews, detection, e-commerce, eWOM, marketing*

# Dataset
The Fake Reviews dataset that contains 20k computer-generated fake reviews and 20k human-created product reviews can be downloaded here: https://osf.io/tyue9/

# docs/proposal
Contains basic exploration of the chosen language models: ULMFiT and GPT-2.

# nbs
Contains experiments generating and detecting fake reviews.

