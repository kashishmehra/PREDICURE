# PREDICURE
Detection of any disease form various symptoms of the patients has always been a major issue 
for the medical practitioner and pathologist for diagnosis and treatment planning. It is also a 
fact that some tests may be time consuming and difficult for the pathologists to obtain the 
accuracy of the presence of any disease. This project uses the image processing techniques to 
help the end user to automatically classify the disease by providing the image of affected area 
as input.The project aims at designing an automated computer based multiple disease classification 
system. Models used would be trained using large datasets (around 11k for skin, 14k for covid-19 and
11k for brain) to acquire high accuracy unlike the previous implementations available.

A website is built where a person can upload an image from the UI. The image would 
be sent to the trained model. The model would then analyze the image and detect whether the 
person is suffering from the disease or not.

## Methodology
The various stages involved for the detection of disease using image processing are 
preprocessing of images, feature extraction and the classification. The proposed approach is 
simple, fast and does not require expensive equipment other than a computer or a mobile phone. 
We resize the image to extract features using pre-trained convolutional neural network. After 
that classify feature using CNN. Finally, the results are shown to the user, including the type 
of disease, spread, and severity. 
1. The first step is the image acquisition stage which starts with taking a collection of images 
from the database.
2. Second step includes image processing i.e. the finer details of images are enhanced and 
noises are removed from the images. Functions performed by preprocessing process is Gray 
scale conversion, noise removal and contrast enhancement. 
3. Third stage is feature extraction using convolutional neural network (CNN). 
4. Last stage is classification stage. Classification provides the answer whether the image 
contains brain tumor or not and same for others as well. For classification we have used CNN 
classifier.

<img align="center" height="300" width="500" alt="GIF" src="https://github.com/kashishmehra/PREDICURE/blob/main/methodology%20flowchart.jpeg?raw=true" />

## Block Diagram for the Predicure System

<img align="center" height="300" width="500" alt="GIF" src="https://github.com/kashishmehra/PREDICURE/blob/main/blockdiagram%20for%20prediure.jpeg?raw=true" />

## Block Diagram for Disease Prediction

<img align="center" height="300" width="500" alt="GIF" src="https://github.com/kashishmehra/PREDICURE/blob/main/block%20diagram%20for%20prediction%20of%20disease.jpeg?raw=true" />
