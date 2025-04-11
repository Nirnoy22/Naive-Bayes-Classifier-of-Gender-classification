# Naive-Bayes-Classifier-of-Gender-classification
Naive Bayes Classifier of Gender classification

**About the Project:**

We deploy the trained model to classify the gender of new instances based on their features. This project demonstrates the application of Naive Bayes in real-world classification tasks and highlights its strengths and limitations in handling categorical data for gender classification.

In this project, our goal is to create a gender classification model using the Naive Bayes algorithm. The dataset contains various features like 'long_hair', 'forehead_width_cm', 'forehead_height_cm', 'nose_wide','nose_long', 'lips_thin', 'distance_nose_to_lip_long', along with the gender label ('male' or 'female').

We begin by preparing the data and encoding categorical features. Then, we divide the dataset into training and testing sets.

Next, we train a Naive Bayes classifier on the training set. Naive Bayes is suitable for this task due to its simplicity and effectiveness in handling categorical data. It assumes that the presence of a particular feature in a class is independent of the presence of any other feature, which is often a reasonable assumption for this type of dataset.

Once the model is trained, we assess its performance on the testing set using metrics like accuracy, precision. We also examine the model's performance across different examples.

Here we have also shown an accurecy comparison of different types of Naive Bayes classifier, and choosen the best Classoifier.

Finally, we deploy the trained model to classify the gender of new instances based on their features. This project demonstrates the application of Naive Bayes in real-world classification tasks and highlights its strengths and limitations in handling categorical data for gender classification.

**About the DataSet:**

The gender dataset contains various features like :

**long_hair :** This indicates whether this person has a long hair or not.

**forehead_width_cm :** The width of the forehead from right to left given in cm.

**forehead_height_cm :** The width of the forehead width in cm from where the hair grows to the eyebrows.

**nose_wide :** Whether the nose is wide or not. 1 represents wide and 0 not.

**nose_long :** Whether the nose is long or not. 1 represents long and 0 not.

**lips_thin :** Whether this person has a thin lip or not. 1 represents thin and 0 not.

**distance_nose_to_lip_long :** It is the distance from nose to lip is long? 1 represents yes and 0 not.

**gender :** It either Male or Female.
