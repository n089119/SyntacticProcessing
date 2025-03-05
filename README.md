Problem Statement
BeHealthy has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions. So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

Datasets
There are four datasets provided to you to process, which are as follows: train_sent test_sent train_label test_label

Actions:
You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
After that, you need to define the features to build the CRF model.
Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
Once the features are computed, you need to define the target variable and then build the CRF model.
Then, you need to perform the evaluation using a test data set.
After that, you need to create a dictionary in which diseases are keys and treatments are values.
There are eight major tasks that you need to perform to complete the assignment. They are as follows:

Data preprocessing
Concept identification
Defining the features for CRF
Getting the features words and sentences
Defining input and target variables
Building the model
Evaluating the model
Identifying the diseases and predicted treatment using a custom NER
![image](https://github.com/user-attachments/assets/592f9261-d640-4b2e-ad6a-28f04ae174b2)

