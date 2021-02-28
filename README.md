# DSC680 Project 1 - Generate Product Reviews
This project was an attempt to use an LSTM model to generate coherent text in the form of a product review on Amazon. The results left much to be desired, contained in this repo are:


## Archive (folder)
This was an initial pass at the project. Nothing in here is required for reviewing this project. This is just kept as reference for myself.

## Results (folder)
This is where results of the training are output. You can review the output in here and see how miserable my model performed. :)

## Notebooks
generate-product-reviews: This is where I put together a model and attempt to train it

product-review-eda: This, as the name states, is where I do some exploratory analysis. 

# DSC680 Project 2 - Breast Cancer Prediction
This project was an attempt to use an CNN model against images to detect the occurence of breast cancer.

## Summary 
It used histopathological images as part of a modified version of the PCam dataset. It was pulled from a Kaggle competition.
 
The model was a CNN that looked for a single pixel of cancer in a 32px x 32px region of the image.

## Notebooks
breast-cancer-eda-gpu.ipynb: Exploratory analysis, attempting to use GPU on Google Colab
breast-cancer-eda.ipynb: Exploratory analysis
breast_cancer_success.ipynb: Full notebook, include some of the EDA from above. Makes use of a GPU on Colab. Also contains the model and the results of the model

# DSC680 Project 3 - Image Captioning
This project was an attempt to caption images from the Flickr8k dataset. 

## Summary 
It used the provided image captions as a vocabulary for my caption generator. 
 
This project used transfer learning from an existing CNN model trained on the ImageNet dataset.
It then used an LSTM model to generate the captions based on the features extracted from the images.

## Notebooks
image_captioning_v2.ipynb: Contains setup, EDA, and model. Built using Google Colab.
