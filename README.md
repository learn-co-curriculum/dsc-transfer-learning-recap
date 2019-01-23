
# Section Recap

## Introduction

This short lesson summarizes key takeaways from section 44.

## Objectives
You will be able to:
* Understand and explain what was covered in this section
* Understand and explain why this section will help you become a data scientist

## Key Takeaways

The key takeaways from this section include:

* Convolutional bases or pretrained networks are particularly useful when your data at hand is limited
* In general, the first few layers of convolutional bases detect very general features such as edges, therefore, pretrained networks can be used on completely different classes of images they were originally trained on
* Two ways of using convolutional bases include: feature extraction and fine-tuning
* Feature extraction involves using a pretrained network, running new data through it, and training a _new_ classifier on top of that
* fine-tuning involves "unfreezing" a few top layers from the model and training them again together with the densely connected classifier
* Several convolutional bases are available in Keras, and you learned how to perform both feature extraction and fine-tuning
