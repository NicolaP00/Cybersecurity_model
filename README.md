For the cybersecurity exam, we chose to focus on the topic of ML techniques for Intrusion Detection Systems, leveraging the capabilities of ML algorithms to detect malicious anomalies by analyzing data behavior. After documenting and explaining the problem, existing algorithms, and their respective pros and cons, we opted to test several common ML models to compare their performance. We selected the NSL-KDD dataset, an updated version of one of the most widely used IDS datasets, KDDCup99. Our objective is to build and train multiple ML models capable of distinguishing between normal behavior and anomalies. Intrusions are categorized as DoS, Probe, U2R, or R2L. Recognizing the 'no free lunch' theorem, we acknowledge that each ML model has its limitations. Consequently, by the end of the study, we test a hybrid ensemble combining various ML models.

## Files

This repo contains a notebook called Cyber.ipynb, in which all the code is written, and two txt files KDDTrain+ and KDDTest (the used datasets)

### NSL-KDD

The NSL-KDD dataset comprises a training set containing over 120,000 labeled data instances and a test set consisting of more than 22,000 samples. Each sample in the dataset is characterized by 41 features, along with its corresponding label and difficulty rating.

### Cyber.ipynb

Cyber.ipynb is a comprehensive notebook that explores various machine learning (ML) models for the task of intrusion detection. The notebook is structured as follows:
- Analysis of the dataset and preprocessing steps.
- Application of dimensionality reduction techniques.
- Initialization and training of different ML models.
- Evaluation of model performance using validation and test datasets.
- Implementation of an ensemble model.
- Development of a Convolutional Neural Network (CNN) for intrusion detection.
