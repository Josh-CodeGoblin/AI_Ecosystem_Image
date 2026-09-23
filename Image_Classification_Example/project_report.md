# Image Classification and Processing Project

## Part 1: Image Classification

I used the provided image classifier on an image of an axolotl. The model correctly predicted the image as an axolotl with approximately 97% confidence.

The top three predictions were:

1. Axolotl - 0.97
2. Banded Gecko - 0.00
3. Sea Slug - 0.00

The results showed that the classifier was very confident in its main prediction.

## Grad-CAM Heatmap Analysis

The Grad-CAM heatmap showed that the classifier focused strongly on the axolotl's face, mouth, and external gills. These are some of the most recognizable physical features of an axolotl.

The model also showed some attention around the front legs, while much of the background received less attention. This helped me understand that the classifier was using meaningful features of the animal when making its prediction instead of mainly relying on the background.

## Part 2: Image Filters

The starter blur filter resized the image and used a Gaussian blur to soften details in the picture.

I also tested the spaghetti filter included in the example program.

For my custom filter, I created a vivid image effect. The filter uses ImageEnhance to increase color saturation, contrast, and sharpness.

- Color enhancement makes the colors stronger.
- Contrast makes the light and dark areas more noticeable.
- Sharpness makes edges and smaller details stand out.

The finished image had a brighter and more dramatic appearance than the original image.

## AI Collaboration Reflection

Working with the AI assistant helped me understand the classifier, Grad-CAM, and image filter code more clearly.

One of the biggest challenges was setting up the Python environment. TensorFlow did not support the original Python 3.14 version installed in WSL, so I created a Python 3.12 virtual environment. I also ran into memory problems while installing the required packages and had to troubleshoot WSL before everything worked correctly.

Another challenge was an indentation error caused by mixing tabs and spaces while adding my custom filter. I used Python's compile check to find and correct the problem.

The AI assistant helped explain the errors instead of only giving me commands to copy. Once the environment was working, I was able to run the classifier, analyze the Grad-CAM heatmap, test the provided filters, and create my own vivid filter.

This project helped me understand how AI can assist programmers with debugging, explaining code, and developing a solution step by step.

https://github.com/Josh-CodeGoblin/AI_Ecosystem_Image/tree/main/Image_Classification_Example
