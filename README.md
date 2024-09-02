# Waste-Segregation-System
The project aims to develop an automated waste segregation system using Machine learning techniques and pre-trained models like ResNet50, which will ultimately contribute to sustainable waste management practices through the synergy of advanced technologies and environmental stewardship.
## Introduction
This project intends to investigate the efficacy of several machine learning
algorithms for automating waste segregation processes, such as SVM,
decision tree, random forest, and ResNet50. Additionally, SMOTE is used for
data augmentation to resolve imbalanced datasets and increase model
accuracy.
## Dataset
●Sourced French waste classification dataset from Kaggle.
●Total of 7190 image files (JPG/JPEG format).
●Divided into Training Set (7033 images) and Test Set (157
images).
●Six distinct classes: 'Cardboard_brick', 'Glass_bottle',
'Household_garbage', 'Metal_packaging', 'Paper_cardboard',
'Plastic_bottle'.
Link to Data: https://www.kaggle.com/datasets/manonstr/tipe-webscraping
## Data Preparation:
Since our dataset was in French language, so we converted the directory
names and each image file names into respective translations in English
using the os module provided in python.
## Data Cleaning:
● In the data cleaning phase, meticulous efforts were undertaken to ensure the integrity and quality
of the dataset used for training our model.
● Firstly, GIF images were identified and subsequently excluded from the dataset to maintain a
consistent format, focusing on the widely supported JPG/JPEG images.
● Additionally, the identification and removal of 1-2 corrupt files that could potentially compromise
the model's training process.
● Exclusion of certain blurry images.
● the dataset was reduced to a total of 7018 image files.
This strategic elimination lead to contributing to a more robust and accurate waste classification
model.
## Data Augmentation:
During training, we used a technique called data augmentation to make the our model more adaptable and
prevent it from focusing too much on specific examples (overfitting). This
● involved creating new versions of our images by flipping them, rotating them,and zooming in or out.
● we gave the model a more diverse set of examples to learn from, helping it become better at recognizing
different types of waste. This way, when faced with new, unseen images, the model is more likely to
make accurate predictions.
● Data augmentation is like giving the model a variety of scenarios to learn from, making it more flexible
and effective in classifying waste.

## Model Training:
We have leveraged ML techniques like Logistic Regression, KNN, Decision Tree, SVC and Random Forest. A deep neaural network CNN and a pre-trained model (ResNet-50) is also utilized in this project. Highest accuracy achieved was by Random forest which is 87%.
