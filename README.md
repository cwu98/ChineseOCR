# ChineseOCR
Optical character recognition (OCR) system for recognizing handwritten Chinese characters

## Description: 
An optical character recognition (OCR) system that aims to recognize handwritten Chinese characters and output a machine-encoded text character. I wanted to create on OCR system for Chinese so that humans can easily input unknown handwritten text characters into softwares such as Pleco, Google Translate, and search bars for translations and search results. 

See ChineseOCR_Presentation file for a more detailed presentation of the project.

## Machine Learning Model:
A 3-layer convolutional neural network (CNN) is the model that was used to train the data to classify images of handwritten characters to their respective labels. We chose to use 70 labels/characters to have the system recognize and classify. After training the model, we ended up with an accuracy of .93 on the testing set. 

*For more details, see pdf doc titled "OCR for Handwritten Chinese Characters using CNN"*
