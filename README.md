# Final Thesis Code - Mirle Willems - 2002654

This repository exists of the following elements:

## Attribute classifiers:
This folder contains code for training all Attribute classifiers. These classifiers are divided into three main attributes: Hood, Closure, Length and Style. Moreover, it contains, per main attribute, the code to split the dataset inot train, test and valiation set. 


## Linear SVMs
This folder contains code to fit all Linear SVMs, calculate the conditional entropy and plot the t-SNE plot, divided per attribute. 


## Splitting data - One vs Rest approach
This folder contains the code to split the dataset of non-binary attributes into binary ones and includes the csv files with the images and corresponding labels.


## StyleGAN respository
This folder contains all scripts originated from the StyleGAN repository that has been altered or added to perform this research.

#### attribute_vector_images.py
to perform (controlled) single attribute manipulation

#### multiple_attribute_manipulation.py 
to perform (controlled) multiple attribute manipulation

#### run_latents_linear_separability.py 
generate images and perform pseudo-labelling

#### pretrained_example.py 
generate pseudo-labelled images to investigate

#### Scripts that were minimally changed to train a StyleGAN
train.py, run_metrics.py, metric_base.py

#### Scripts originating from the original StyleGAN repository that were alted
pretrained_example.py, run_latents_linear_separability.py

#### Script that I wrote with pieces of codes originating from the original StyleGAN repository
attribute_vector_images.py, multiple_attribute_manipulation.py

#### Article used to train StyleGAN with own dataset
https://evigio.com/post/how-to-use-custom-datasets-with-stylegan-tensorFlow-implementation


#### Attribute Vectors Correlation Matrix
Contains the code to create the correlation matrix of the attribute vectors.


### Exploration PIM Dataset
Contains the code that explored the PIM dataset.


### Resize and Reshape scraped images Zalando
Contains the code to preprocess the scraped images of Zalando.
