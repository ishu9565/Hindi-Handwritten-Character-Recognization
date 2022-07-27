# Handwritten Hindi Word Recognition

The original dataset has been taken from the below mentioned site. The link for the data - 
![](https://archive.ics.uci.edu/ml/datasets/Devanagari+Handwritten+Character+Dataset) Since the dataset was huge, I haven't uploaded it here.

This aims at classifying handwritten Hindi letters into 36 classes. The dataset consisted of 61200 32X32 images. Each image was greyscaled. The entire data was divided into three parts training, validation and test set. The model has been currently trained only for the consonants, vowels can also be added.



## CHARACTER SET:

क, ख, ग, घ, ड़, च, छ, ज, झ, ञ, ट, ठ, ड, ढ, ण, त, थ, द, ध, न, प, फ, ब, भ,म, य, र, ल, व, श, ष, स, ह, क्ष, त्र, ज्ञ

## WORKFLOW:
![image](https://user-images.githubusercontent.com/60650077/181167494-d7d123d2-3bd1-4363-939c-e6ffe6840f36.png)

## steps 
1. **Word segmentation** enables the character recognition of paragraphs, preserving the order of the words
2. **Character segmentation** enables the character recognition of a word
3. **Image processing** enables the segmentation of slanted words and characters, and *svar* having a *matra*
4. **Data augmentation** using image data generator class, rotated, shifted, sheared and zoomed
5. **Convolution neural network** helps in feature extraction

## To run on your local system:
* Clone the repository
* Install all dependencies requirments.txt
* Carefully check on which image you want to run as well as it is in images folder or not.
* Finally run main.py(driver code).

## Some Examples:

* ![](https://github.com/Bellicose-YB/Devnagiri-Handwritten-Word-Recognition/blob/main/images/lol.JPG)
* ![](https://github.com/Bellicose-YB/Devnagiri-Handwritten-Word-Recognition/blob/main/images/Capture.PNG)
